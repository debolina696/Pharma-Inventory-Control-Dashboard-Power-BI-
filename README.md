📊 Pharma Analytics – Power BI End-to-End Project
🔍 Project Purpose
This project delivers an end-to-end Power BI analytics solution for a pharmaceutical organization, designed to support data-driven decision-making across HR, inventory, and employee performance.
The solution transforms raw operational data into actionable business insights using:
Advanced DAX calculations
Dynamic KPIs and selectors
Interactive slicers, tooltips, and drill-through
Optimized data modeling and helper columns
The dashboards enable stakeholders to monitor workforce structure, inventory risk, and employee performance in a single integrated analytics system.
🧑‍💼 Page 1: Employee HR / Employee Inventory Analysis
🎯 Page Objective
This page provides a holistic view of the organization’s workforce by analyzing:
Headcount and demographics
Salary and tenure distribution
Hiring and promotion trends
Workforce experience and retention indicators
It helps HR teams identify workforce stability, experience gaps, promotion patterns, and gender distribution.
📌 Key KPIs Covered
Total Employees
Average Salary
Average Tenure
Department Count
Location Count
Male % / Female %
Employees Joined in 2024
Employees Joined in March 2024
Employees Worked > 5 Years
Promotion Count (>2)
Oldest Employee Age
Youngest Employee Age
➡️ KPIs are controlled using a Dynamic KPI Selector for a clean and interactive KPI panel.
📊 Visuals Used & Why
Department-Wise Promotion Distribution (Donut Chart)
Identifies promotion concentration across departments.
Department-Wise Tenure (Bar Chart)
Highlights employee retention and experience level by department.
Age Group-Wise Employee Count (Bar Chart)
Shows workforce age structure for succession planning.
Age Group-Wise Salary Distribution (Bar Chart)
Validates salary alignment with employee age groups.
Gender-Wise Salary Distribution (Bar Chart)
Supports pay equity analysis.
Year & Month-Wise Employee Hiring Trend (Line Chart)
Tracks time-based hiring patterns and workforce growth.
Top 5 Trained Employees (Bar Chart)
Identifies highly skilled and upskilled employees.
Employee Detail Table
Enables record-level validation and drill-through analysis.
🧠 Advanced DAX & Calculations Used
Dynamic KPI Switching
SWITCH(), SELECTEDVALUE()
Used for KPI selector and dynamic KPI cards
Tenure & Experience Calculations
DATEDIFF(), TODAY()
Used to calculate years worked and experience buckets
Age Analysis
MAX(), MIN(), calculated age columns
Used to identify oldest and youngest employees
Time-Based Hiring Analysis
YEAR(), MONTH(), filter context
Used for year & month-wise hiring trends
Promotion Logic
Conditional filters and helper columns
Used to identify employees with multiple promotions
Gender Percentage Calculation
DIVIDE(), COUNTROWS(), CALCULATE()
Used for Male % and Female %
⚙️ Advanced Features Implemented
Dynamic KPI selector with interactive cards
Helper columns for age, tenure, and promotion categorization
Drill-through enabled employee detail analysis
Custom tooltips for contextual insights
Fully interactive slicers (Year, Month, Department, Gender, Promotion)
💼 Business Value
Improves HR visibility into workforce structure and experience
Supports retention strategy through tenure and age analysis
Identifies promotion concentration and gaps
Enables pay equity and demographic analysis
Helps HR leaders make data-driven workforce decisions
Dashboard Link - "C:\Users\Debolina\OneDrive\Pictures\Screenshots\Emp HR Dashboard.png"


