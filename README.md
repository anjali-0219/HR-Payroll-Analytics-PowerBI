# 📊 HR & Payroll Analytics Dashboard – Power BI

An interactive **HR & Payroll Analytics Dashboard** built using **Microsoft Power BI** to analyze employee information, salaries, payroll, departments, budgets, bonuses, and workforce trends.

The project transforms employee and payroll data into interactive dashboards using **Power BI, DAX, Power Query, data modeling, and data visualization**.

---

## 📌 Project Overview

The HR & Payroll Analytics Dashboard provides a centralized view of employee and payroll-related information.

The dashboard helps HR teams and management analyze:

- 👥 Employee workforce
- 🏢 Department-wise employee distribution
- 💰 Salary and payroll
- 🎁 Bonuses and deductions
- 👨‍💼 Employee designations
- 👨‍🦰 Gender distribution
- 📅 Joining-year trends
- 📈 Payroll trends
- 💼 Department budgets
- 📊 Department performance

The report contains multiple interactive dashboard pages with slicers, KPI cards, charts, and drill-through functionality.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze total employee count.
- Analyze employees by department and designation.
- Compare male and female employees.
- Calculate average salary and experience.
- Analyze payroll and salary trends.
- Analyze bonus and deduction information.
- Compare departmental salaries.
- Analyze department budgets.
- Identify highest-paying departments.
- Analyze employee joining trends.
- Create interactive HR and payroll reports.
- Provide meaningful insights through Power BI visualizations.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Microsoft Power BI** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures and calculations |
| **Data Modeling** | Connecting tables and creating relationships |
| **Power BI Visuals** | Charts, KPI cards, tables and slicers |

---

## 📂 Dataset

The project uses employee, salary, department, and calendar-related data.

### Main Tables

#### `fact_salary_dataset`

Contains salary and payroll-related information.

Important fields include:

- EmployeeID
- Salary
- Bonus
- Budget
- HRA
- Net Salary
- Payroll-related fields

#### `employee_dataset`

Contains employee information.

Important fields include:

- EmpID
- Gender
- Designation
- Employee details

#### `dept_dataset`

Contains department information.

Important field:

- DeptName

#### `Dim calander`

Calendar/date dimension used for time-based analysis.

Important fields:

- Date
- Month
- Month Name
- Year
- Quarter

---

# 📊 Dashboard Pages

## 1️⃣ HR & Payroll Overview

This page provides a high-level overview of the organization's workforce and payroll.

### KPIs

- Total Employees
- Total Payroll
- Total Bonus
- Total Deductions
- Average Salary
- Salary-related metrics

### Visualizations

- Payroll by Department
- Employees by Department
- Payroll Trend
- Employees by Gender

### Filters

- Department
- Location
- Gender
- Year

---

## 2️⃣ Employee Analysis

This page focuses on employee demographics and workforce composition.

### KPIs

- Total Employee Count
- Male Employees
- Female Employees
- Average Experience

### Visualizations

- Employees by Designation
- Employees by Gender
- Employees by Joining Year
- Employees by Department
- Employees by Experience
- Salary Overview

### Filters

- Department
- Gender
- Designation
- Year

---

## 3️⃣ Employee Drill-Through

This page provides detailed employee-level analysis.

### Employee Information

- Employee ID
- Employee Name
- Department
- Designation
- Gender

### HR & Salary Information

- Joining Date
- Experience
- Salary
- Bonus
- HRA
- Base Salary
- Total Salary
- Net Salary

### Purpose

The drill-through feature allows users to select an employee from another dashboard and view detailed information about that employee.

---

## 4️⃣ Department Analysis

This page focuses on department-level analysis.

### KPIs

- Total Departments
- Total Employees
- Total Budget
- Average Budget
- Average Department Size

### Visualizations

- Employees by Department
- Budget vs Spent by Department
- Average Salary by Department
- Employees by Department (%)
- Department-wise Headcount Trend
- Department Summary

### Filters

- Department
- Location
- Manager
- Budget Range
- Year

---

### Project Structure

HR-Payroll-PowerBI/
│
├── README.md
│
├── HR_Payroll_Dashboard.pbix
│
├── dataset/
│   └── employee_salary_dataset.csv
│
└── screenshots/
    ├── dashboard_overview.png
    ├── employee_analysis.png
    ├── employee_drillthrough.png
    └── department_analysis.png

## 👩‍💻 Author

**Anjali Patnaik**

**Project:** HR & Payroll Analytics Dashboard  
**Domain:** Human Resources & Payroll Analytics  
**Technology:** Microsoft Power BI
