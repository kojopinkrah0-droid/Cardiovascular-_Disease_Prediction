# Analysis summary

## Dataset profile

- Rows: **42,640**
- Columns: **29**
- Years: **2004–2013**
- Locations: **52** unique abbreviations
- Topics: **6**
- Missing `Data_Value`: **529 (1.2%)**
- Exact duplicate rows: **0**

## Evidence-based descriptive findings

1. The dataset contains 42,640 rows and 29 columns, covering 2004–2013.
2. 529 records (1.2%) have a missing Data_Value; these estimates were retained as missing rather than imputed.
3. No exact duplicate rows were found in the original dataset (0).
4. The highest mean Data_Value among topics is Major Cardiovascular Disease (23.84); the lowest is Acute Myocardial Infarction (Heart Attack) (2.87).
5. The highest yearly mean is 2004 (17.04) and the lowest is 2013 (13.56); these are pooled descriptive means, not adjusted rates.
6. Among non-US locations with at least 20 non-missing observations, the highest mean is West Virginia (18.94; n=787).
7. The mean Data_Value differs across breakout categories; the highest category mean is Race (15.96).
8. Data_Value ranges from 0.40 to 333.30; extreme values should be checked against indicator definitions and confidence limits before interpretation.

## Important interpretation notes

- This is a location/year/topic/breakout-level cardiovascular hospitalization dataset, not a person-level dataset for predicting whether an individual has heart disease.
- The `Data_Value` measure varies by indicator and breakout and must be interpreted alongside `Indicator`, `Data_Value_Unit`, `Data_Value_Type`, and footnotes.
- Pooled averages across indicators or groups can be misleading because populations, measures, and denominators may differ. Use within-indicator comparisons for stronger conclusions.
- The data span 2004–2013 and should not be presented as current health statistics.
- Association and descriptive differences do not establish causation.
