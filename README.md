# GBD-Metabolism-associated-MASLD-in-younger-patients
Global, Regional, and National Burden of Early-Onset Gastrointestinal Malignancies Attributable to Metabolic Dysfunction: An Age-Period-Cohort Analysis (1990-2023).

#Search-stratergy
#Search 1: The APC Matrix (Baseline Disease Burden)
This pull creates the foundation for your APC models, tracking the raw incidence and mortality of the GI cluster.
GBD Estimate: Cause of death or injury
Measure: Incidence, Deaths, and DALYs
Metric: Number and Rate (You need "Number" for the Decomposition analysis to calculate absolute case growth, and "Rate" for the APC modeling).
Cause:
Liver cancer due to NASH
Colon and rectum cancer
Pancreatic cancer
Gallbladder and biliary tract cancer
Location: * Global
The 5 SDI Regions (High, High-middle, Middle, Low-middle, Low)
The 21 GBD Regions (e.g., Australasia, Western Europe)
Age: Do not select an aggregated range like 15–49. You must select the distinct 5-year bands:
25 to 29
30 to 34
35 to 39
40 to 44
45 to 49
Sex: Male and Female (Keep them separated to analyze gender disparities in metabolic risk).
Year: Select every individual year from 1990 to 2023. You need the continuous timeline for the "Period" effect in your regression models.

#Search 2: The Metabolic PAFs (Risk Attribution)
This pull isolates the specific metabolic drivers, allowing you to prove that the trends in Search 1 are fundamentally tied to metabolic dysfunction.
GBD Estimate: Risk factor (Change the top dropdown)
Measure: Deaths and DALYs
Metric: Add Percent alongside Number and Rate. (The "Percent" metric provides your Population Attributable Fractions).
Risk:
High body-mass index
High fasting plasma glucose
Cause: Select the exact same four GI cancers as Search 1.
Location, Age, Sex, Year: Keep these parameters completely identical to Search 1.
