# Power BI Report: Grade 12 Mathematics Performance

## Data Preparation

Before creating the report, I performed **data profiling** to examine the data structure, content, quality, and relationships. I checked for completeness, duplicates, and consistency in the dataset.

Next, I applied the **ETL process**:

- **Extract:** Imported the Excel dataset into Power BI.  
- **Transform:** Used Power Query to clean the data, check data types, and remove duplicates.  
- **Load:** Loaded the cleaned data into Power BI for analysis.

---

## Report Overview

The report focuses on **Grade 12 Mathematics performance** for two schools, comparing students from **Urban** and **Rural** areas. The goal is to identify factors affecting student performance.

### Filters (Slicers) Used:

- School Name  
- Sex  
- Support Group (measure combining school support, internet access, and family support)  
- Address (Urban/Rural)  

### KPI Cards:

- **Total Students:** 395 (Urban: 307, Rural: 88)  
- **Pass Rate %:** Students with final marks ≥ 10 (Urban: 210 passed, Rural: 55 passed)  
- **Fail Rate %:** Students with final marks < 10 (Urban: 97 failed, Rural: 33 failed)  
- **Average Final Marks (G3):** Average of final grade for all students  

---

## Visuals

1. **Total Students by Performance Status:**  
   Shows 265 students passed and 130 failed overall.

2. **Performance by Address:**  
   - Urban: 210 passed, 97 failed  
   - Rural: 55 passed, 33 failed  

3. **Support Group by Address:**  
   - Urban: 295 students have support  
   - Rural: 70 students have support  

4. **Extra Classes Attendance:**  
   - 181 students attended extra classes  
   - 214 students did not attend  

---

## Additional Features

- **Reset All Filters Button:** Clears all selected filters.  
- **Detail Report Button:** Drill-through to the filtered student dataset for further analysis or export to Excel/CSV.

---

## [View Interactive Report](YOUR_PUBLISH_TO_WEB_LINK_HERE)
