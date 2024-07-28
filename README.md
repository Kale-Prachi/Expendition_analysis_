# Expendition_analysis_ using_excel
The data includes expedition details such as peak names, countries attempting climbs, deaths, summit successes, causes of deaths, oxygen usage, failed climbs, climbing seasons, and different routes.

**Data Cleansing:**
The data required significant cleaning:
Removed duplicate rows.
Eliminated columns with more than 80% missing data.
Created a new column for the reason for death (e.g., simplified “fall (8576)” to just “fall”).

**Data Modeling:**
I have three tables: expedition data, death data, summit data, and peak data, linking them via a common column, peak_id.

**Exploratory Data Analysis (EDA):**
Performed various EDA operations and created pivot tables.

**Reporting:**
Developed a dashboard using different charts (bar, column, pie) with filters for a comprehensive view.

**Key Insights:**
1. Everest is the highest mountain.
2. The success rate of Everest expeditions is high, followed by Ama Dablam.
3. Falls are the primary cause of death.
4. Most deaths occur in the spring season.
5. Dan Mazur is the best leader for climbing expeditions.
6. Japan frequently participates in Himalayan climbs.
7. Oxygen is mainly used for medical purposes on Everest and Cho Oyu.
8. Oxygen is rarely used on Ama Dablam and during the autumn season.
9. On Everest, oxygen is often used while sleeping.
