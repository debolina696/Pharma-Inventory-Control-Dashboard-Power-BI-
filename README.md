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
- Dashboard image ilink - Screenshot 2025-12-20 205707.png 
