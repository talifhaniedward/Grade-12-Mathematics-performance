Power BI Report: Grade 12 Mathematics Performance
Overview

This report analyzes Grade 12 Mathematics performance for two schools, comparing students from Urban and Rural areas. The goal is to identify factors affecting student performance and provide actionable insights.

Data Preparation

Before creating the report, data profiling was performed to examine the data structure, content, quality, and relationships. Completeness, duplicates, and consistency were checked.

The ETL process was applied as follows:

Extract: Imported the Excel dataset into Power BI

Transform: Cleaned data in Power Query, checked data types, removed duplicates

Load: Loaded the cleaned dataset into Power BI for analysis

Filters (Slicers) Used

School Name

Sex

Support Group (combined measure of school support, internet access, and family support)

Address (Urban/Rural)

KPI Cards

Total Students: 395 (Urban: 307, Rural: 88)

Pass Rate %: Students with final marks ≥ 10 (Urban: 210 passed, Rural: 55 passed)

Fail Rate %: Students with final marks < 10 (Urban: 97 failed, Rural: 33 failed)

Average Final Marks (G3): Overall average of final grades

Visuals

Total Students by Performance Status

265 students passed, 130 students failed

Performance by Address

Urban: 210 passed, 97 failed

Rural: 55 passed, 33 failed

Support Group by Address

Urban: 295 students have support

Rural: 70 students have support

Extra Classes Attendance

181 students attended extra classes

214 students did not attend

Additional Features

Reset All Filters Button: Clears all selected filters

Detail Report Button: Drill-through to the filtered student dataset for further analysis or export to Excel/CSV

Tools & Technologies

Power BI Desktop

DAX (measures and calculations)

Power Query (data transformation)

Excel (data source)

Interactive Report

View Interactive Power BI Report
