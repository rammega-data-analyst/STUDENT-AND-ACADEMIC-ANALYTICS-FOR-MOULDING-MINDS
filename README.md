
# Student and Academic Analytics for Moulding Minds

## Project Overview

This project is developed using **Microsoft Power BI** to analyse student information, attendance, academic performance, teacher performance, admissions, enrollment, and parent feedback.

The objective is to transform raw educational data into meaningful insights through data cleaning, data analysis, KPI development, and interactive dashboard reporting.

## Dashboard Preview



## Project Objectives

- Analyse student distribution across grades, gender, and sections.
- Monitor student attendance performance.
- Evaluate examination and assignment scores.
- Analyse teacher-wise performance indicators.
- Understand admission and enrollment trends.
- Analyse parent feedback ratings.
- Develop an interactive dashboard for institutional insights.

## Dataset Details

| Description | Details |
|---|---|
| Original Records | 2,000 |
| Records After Duplicate Removal | 1,985 |
| Number of Columns | 16 |
| Tool | Microsoft Power BI |

### Dataset Columns

1. Student ID
2. Student Name
3. Gender
4. Date of Birth
5. Admission Date
6. Grade
7. Section
8. City
9. Subject
10. Teacher Name
11. Attendance Percentage
12. Exam Score
13. Assignment Score
14. Activity Participation
15. Parent Feedback Rating
16. Enrollment Status

## Data Cleaning and Transformation

Data preparation was performed using **Power Query Editor**.

- Data profiling using Column Quality, Column Distribution, and Column Profile.
- Duplicate record removal.
- Missing-value identification and handling.
- Text cleaning using Trim.
- Text standardisation.
- Date data type conversion.
- Data quality and error review.

## Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| Total Students | 1,985 |
| Average Attendance | 87.66% |
| Average Exam Score | 71.34 |
| Average Assignment Score | 78.17 |
| Average Parents Feedback Rating | 2.97 |

An Average Attendance percentage measure was created using DAX.

## Charts and Visualisations

A total of **16 charts** were prepared.

### Student Analytics
1. Students by Grade
2. Students by Gender
3. Students by Enrollment Status
4. Students by Activity Participation
5. Students by Section

### Academic Performance Analysis
6. Average Exam Score by Subject
7. Student Performance by Grade
8. Average Assignment Score by Grade

### Attendance Analysis
9. Average Attendance by Grade

### Teacher Performance Analysis
10. Teacher-wise Average Exam Score
11. Teacher-wise Average Assignment Score
12. Teacher-wise Average Attendance

### Admission and Enrollment Analysis
13. Admissions by Year
14. Admissions by Grade
15. Students by Enrollment Status and Grade

### Parent Feedback Analysis
16. Parent Feedback Rating Distribution

## Interactive Slicers

Four interactive slicers were created:

- Grade
- Gender
- Subject
- Enrollment Status

The Sync Slicers feature was used to synchronise slicers across four report pages.

## Final Dashboard Components

The final dashboard layout includes:

- 5 KPI Cards
- 4 Interactive Slicers
- 6 Selected Charts

### Six Main Dashboard Charts

1. Students by Enrollment Status
2. Average Exam Score by Grade
3. Average Attendance % by Grade
4. Students by Gender
5. Average Score by Subject
6. Parent Feedback Rating by Grade

The remaining charts are retained in the Power BI report for detailed analysis.

## Business Recommendations

- Monitor attendance by grade and identify areas requiring improvement.
- Review examination and assignment performance to provide focused academic support.
- Evaluate teacher-wise performance indicators.
- Monitor admission and enrollment trends for better planning.
- Review parent feedback and improve communication and student support.

## Tools and Technologies Used

- Microsoft Power BI
- Power Query Editor
- DAX (Data Analysis Expressions)
- Data Cleaning
- Data Transformation
- Data Visualisation
- KPI Development
- Interactive Slicers
- Dashboard Design

## Project Outcome

This project demonstrates an end-to-end data analytics workflow using Microsoft Power BI, from dataset preparation and data cleaning to KPI development, chart creation, slicer synchronisation, and dashboard design.

## Conclusion

The project provided practical experience in transforming raw educational data into meaningful analytical reports. It demonstrates the use of Power BI for data preparation, performance analysis, interactive reporting, and dashboard development to support data-informed institutional decisions.

