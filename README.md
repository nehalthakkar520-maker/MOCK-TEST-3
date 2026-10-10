Data Analysis Practical Exam - Set C
Project Overview
This project was created as part of the Data Analysis Practical Exam.

The main business question of this project is:

Which course needs the most academic support, and how does performance differ across batches?

The analysis was performed using:

Excel
SQL
Python
Power BI
Dataset
The dataset contains assessment records for different courses and batches.

Courses
Course ID	Course	Department
C1	Excel	Business
C2	PowerBI	Business
C3	SQL	Technology
C4	Python	Technology
Assessment Columns
assessment_id
month
course_id
batch
score
attendance_pct
pass_flag
The original dataset contained 13 assessment records, including one duplicate record.

After removing the duplicate:

Clean Records: 12

1. Excel Analysis
Excel was used for data cleaning, lookup, calculations, PivotTable analysis and visualization.

Excel Work
Removed duplicate record
Added Department using lookup
Created Pass Flag
Used COUNTIFS for batch analysis
Created PivotTable
Calculated average score by department and month
Created column chart
Pass Flag Formula
=IF(E2>=50,1,0)
