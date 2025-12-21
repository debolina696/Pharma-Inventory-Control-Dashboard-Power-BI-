# 📊 Pharma Analytics – Power BI End-to-End Project

## 🔍 Project Purpose
This project delivers an **end-to-end Power BI analytics solution for a pharmaceutical organization**, designed to support **data-driven decision-making across HR, inventory, and employee performance**.

The solution transforms raw operational data into **actionable business insights** using advanced analytics techniques and interactive reporting.

---

## 🧑‍💼 Page 1: Employee HR / Employee Inventory Analysis

### 🎯 Page Objective
This page provides a **holistic view of the organization’s workforce** by analyzing headcount, demographics, salary structure, tenure, hiring, and promotions.

It helps HR teams identify:
- Workforce stability  
- Experience gaps  
- Promotion patterns  
- Gender distribution  

---

## 📌 Key KPIs Covered
- Total Employees  
- Average Salary  
- Average Tenure  
- Department Count  
- Location Count  
- Male % / Female %  
- Employees Joined in 2024  
- Employees Joined in March 2024  
- Employees Worked > 5 Years  
- Promotion Count (>2)  
- Oldest Employee Age  
- Youngest Employee Age  

> KPIs are controlled using a **Dynamic KPI Selector** for a clean and interactive KPI panel.

---

## 📊 Visuals Used & Purpose

- **Department-Wise Promotion Distribution (Donut Chart)**  
  Identifies promotion concentration across departments.

- **Department-Wise Tenure (Bar Chart)**  
  Highlights employee retention and experience by department.

- **Age Group-Wise Employee Count (Bar Chart)**  
  Shows workforce age structure for succession planning.

- **Age Group-Wise Salary Distribution (Bar Chart)**  
  Validates salary alignment with employee age groups.

- **Gender-Wise Salary Distribution (Bar Chart)**  
  Supports pay equity analysis.

- **Year & Month-Wise Employee Hiring Trend (Line Chart)**  
  Tracks time-based hiring patterns and workforce growth.

- **Top 5 Trained Employees (Bar Chart)**  
  Identifies highly skilled and upskilled employees.

- **Employee Detail Table**  
  Enables record-level validation and drill-through analysis.

---

## 🧠 Advanced DAX & Calculations Used

- **Dynamic KPI Switching**  
  `SWITCH()`, `SELECTEDVALUE()`

- **Tenure & Experience Calculations**  
  `DATEDIFF()`, `TODAY()`

- **Age Analysis**  
  `MAX()`, `MIN()`, calculated age columns

- **Time-Based Hiring Analysis**  
  `YEAR()`, `MONTH()`, filter context

- **Promotion Logic**  
  Conditional filters and helper columns

- **Gender Percentage Calculation**  
  `DIVIDE()`, `COUNTROWS()`, `CALCULATE()`

---

## ⚙️ Advanced Features Implemented
- Dynamic KPI selector with interactive cards  
- Helper columns for age, tenure, and promotion categorization  
- Drill-through enabled employee detail analysis  
- Custom tooltips for contextual insights  
- Fully interactive slicers (Year, Month, Department, Gender)

---

## 💼 Business Value
- Improves HR visibility into workforce structure  
- Supports retention strategy through tenure analysis  
- Identifies promotion concentration and gaps  
- Enables pay equity and demographic insights  
- Supports data-driven workforce planning  

---

✅ **This page forms the HR analytics foundation of the Pharma Analytics solution.**  
- Dashboard image ilink - https://github.com/debolina696/Pharma-Inventory-Control-Dashboard-Power-BI-/blob/main/Screenshot%202025-12-20%20205707.png
  ---

## 📊 Page 2: Employee Performance & Sales Effectiveness Analysis

### 🎯 Page Objective
This page analyzes **employee sales performance, efficiency, attendance impact, and promotion outcomes**.

It helps business and HR leaders:
- Identify top and low performers  
- Measure sales efficiency and YoY growth  
- Understand attendance impact on sales  
- Track promotions and performance contribution  

---

## 📌 KPI Questions Answered
- Who are the **top 5 performing employees**?
- How has **employee sales changed YoY**?
- Which employees have the **highest sales efficiency**?
- Does **attendance impact total sales**?
- Which departments contribute most to sales?
- How are promotions distributed across employee positions?

---

## 📌 Key KPIs Covered
- Total Sales  
- Sales Efficiency  
- Performance Score  
- Avg Attendance %  
- YoY % Sales Growth  
- Total Employees  

> KPIs are controlled through a **Dynamic KPI Selector** for a clean and interactive KPI panel.

---

## 📊 Visuals Used & Business Purpose

- **Dynamic KPI Card**  
  Displays selected KPI (Sales, Efficiency, Performance Score, Attendance).

- **Top 5 Performance Score by Employee (Bar Chart)**  
  Identifies highest-performing employees.

- **Top 5 Sales Efficiency by Employee (Bar Chart)**  
  Highlights employees generating maximum sales per effort.

- **3-Year Sales Breakdown by Employee (Stacked Bar Chart)**  
  Shows individual employee sales trend across 2022–2024.

- **YoY % Sales Table (Conditional Formatting)**  
  Highlights growth and decline using color-based rules.

- **Sales Contribution % by Department (Bar Chart)**  
  Shows department-level impact on overall revenue.

- **Promotion Category by Employee Position (Donut Chart)**  
  Analyzes promotion distribution across roles.

- **Attendance Impact on Sales (Bar Chart)**  
  Compares high-attendance vs low-attendance employee sales.

---

## 🧠 Advanced DAX & Logic Used

- **Dynamic KPI Switching**  
  `SWITCH()`, `SELECTEDVALUE()`

- **YoY % Sales Calculation**  
  `CALCULATE()`, `DATEADD()`

- **Performance Score Logic**  
  Custom weighted calculation using sales & attendance

- **Employee Ranking**  
  `RANKX()` for Top 5 performers

- **Aggregation Functions**  
  `SUM()`, `AVERAGE()`

---

## 🎨 Conditional Formatting (Advanced Rules)

- **YoY % Sales Table**
  - Green → Positive Growth  
  - Red → Negative Growth  
  - Yellow → Near-zero change  

- **KPI Cards**
  - Icons and colors based on KPI value direction

---

## 🧩 Tooltips & Interactivity
- Custom **tooltip pages** added to all major visuals  
- Hover interaction shows employee-level insights  
- Cross-filtering enabled across all charts  
- Drill-through supported for employee detail analysis  

---

## 💼 Business Value
- Enables data-driven performance evaluation  
- Helps identify high-impact employees  
- Supports promotion and incentive decisions  
- Improves sales efficiency tracking  

---

✅ **This page acts as the performance intelligence layer of the Pharma Analytics solution.**
- Dashboard Link of Page 2 
