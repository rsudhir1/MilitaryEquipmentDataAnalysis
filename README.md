# MilitaryEquipmentDataAnalysis

EDA and Modelling of Military Equipment Dataset. Final recommendations on equipment that generate the most revenue was provided alongside other trends.

Created a Keras Sequential Model to accurately predict DEMIL Code based on other features.

Meaning of Fields in the Dataset:

NSN, is the equipment code, normally each device has a code (like bar code for storage and reordering)

UI is the unit code, for example the item is a kit or Assembly or individual (each).

DEMIL Code  is the demilitarization code, military releases its equipment with various restrictions. That restriction depends on DEMIL Code.
Code Explanation

G     USML or CCL Military Items – DEMIL required – ammunition and explosives (AE). This code applies to both unclassified and classified AE items.

P      USML Items – DEMIL required. Security classified items.

F      USML or CCL Military Items – DEMIL required. Item managers, equipment specialists, or product specialists must furnish special DEMIL instructions.

D      USML or CCL Military Items – DEMIL required. Destroy item and components to prevent restoration or repair to a usable condition.

C      USML or CCL Military Items – DEMIL required. Remove or demilitarize installed key point(s) items as DEMIL code "D".

E      DoD DEMIL Program Office reserves this code for its exclusive-use only. DEMIL instructions must be furnished by the DoD DEMIL Program Office

B      USML Items – Mutilation (MUT) to the point of scrap required worldwide.

Q      Commerce Control List Item (CCLI) – MUT to the point of scrap required outside the United States. Inside the United States, MUT is required when the DEMIL integrity code (IC) is “3” and MUT is not required when the DEMIL IC is "6."

A      Items subject to the Export Administration Regulations (EAR) in parts 730-774 of Title 15, Code of Federal Regulations (CFR) (CCLI or EAR99) and determined by the DoD to present a low risk when released out of DoD control. No DEMIL, MUT, or end use certificate is required. May require an export license from DOC.
