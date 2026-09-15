# IBM HR Analytics — Employee Attrition & Performance Analysis

## Project Overview

This project analyzes employee data to identify patterns associated with employee attrition and understand factors that may influence workforce retention.

The analysis examines employee demographics, job roles, compensation, overtime, job satisfaction, work-life balance, environment satisfaction, promotion history, and other workforce characteristics.

The objective is to transform employee data into practical HR insights that can help organizations identify higher-risk employee groups and support targeted retention strategies.

---

## Business Problem

Employee turnover can increase recruitment costs, create workforce gaps, and affect team productivity. HR teams therefore need to understand which employee groups have higher attrition rates and which workplace factors are associated with employees leaving the organization.

This analysis focuses on identifying patterns related to:

* Overtime
* Job Satisfaction
* Work-Life Balance
* Environment Satisfaction
* Monthly Income
* Departments
* Job Roles
* Promotion Status

The goal is to provide data-driven insights that support employee retention decisions.

---

## Business Questions

The analysis aims to answer the following questions:

1. What is the overall employee attrition rate?
2. Is overtime associated with higher attrition?
3. How does job satisfaction relate to attrition?
4. Does work-life balance show differences in attrition?
5. Is income level associated with employee attrition?
6. Which departments and job roles have the highest attrition?
7. Which employee groups may require greater retention attention?

---

## Dataset

**Dataset:** IBM HR Analytics Employee Attrition & Performance

* Employees: **1,470**
* Columns: **35**
* Main Outcome: **Employee Attrition**

---

## Tools & Technologies

* Microsoft Excel
* Data Cleaning & Validation
* XLOOKUP
* PivotTables
* PivotCharts
* KPI Calculations
* Interactive Dashboard
* Business Analysis

---

## Data Preparation

The dataset was prepared using Excel through:

* Duplicate checks
* Blank and missing value checks
* Categorical value validation
* Lookup and standardization fields
* Analytical grouping
* Helper columns
* Numeric validation

Additional fields were created for:

* Age Groups
* Income Categories
* Promotion Status
* Attrition Analysis
* Satisfaction Labels

---

## Dashboard Overview

The dashboard focuses on three main areas:

### Overall Attrition

* Total Employees
* Total Attrition
* Attrition Rate
* Average Years at Company
* Attrition by Department
* Attrition by Job Role

### Possible Reasons

* Overtime
* Job Satisfaction
* Work-Life Balance
* Environment Satisfaction
* Monthly Income
* Promotion Status

### Employee Segmentation

Interactive slicers:

* Age Group
* Department
* Job Role
* Business Travel
* Gender
* Marital Status
* Overtime
* Promotion Status

---

## Key Findings

### Overall Attrition

* Total Employees: **1,470**
* Employees Left: **237**
* Attrition Rate: **16.12%**
* Average Years at Company: **7.01**

### Overtime

* Overtime Employees: **30.53% attrition**
* Non-Overtime Employees: **10.44% attrition**

Employees working overtime experienced nearly three times higher attrition.

### Work-Life Balance

* Bad: **31.25%**
* Better: **14.22%**

Poor work-life balance is associated with higher attrition.

### Job Satisfaction

* Low: **22.84%**
* Very High: **11.33%**

Lower job satisfaction is associated with higher attrition.

### Monthly Income

* Low Income: **28.61%**
* Medium Income: **12.03%**
* High Income: **10.80%**

Lower-income employees experienced substantially higher attrition.

### Department

* Sales: **20.63%**
* Human Resources: **19.05%**
* Research & Development: **13.84%**

### Job Role

Highest attrition roles:

* Sales Representative: **39.76%**
* Laboratory Technician: **23.94%**
* Human Resources: **23.08%**

---

## Business Recommendations

* Review overtime and workload management.
* Improve work-life balance initiatives.
* Monitor employee satisfaction regularly.
* Review compensation competitiveness.
* Focus retention efforts on high-attrition job roles.
* Investigate department-level differences.
* Consider multiple factors when evaluating retention risk.

---

## Dashboard
![IBM HR Employee Attrition Dashboard](Dashboard/IBM_HR_Employee_Attrition_Dashboard.png)


Example:

```markdown
![Dashboard](Dashboard/IBM_HR_Employee_Attrition_Dashboard.png)
```

---

## Project Structure

```text
IBM-HR-Analytics-Employee-Attrition/
│
├── README.md
│
├── Data/
│   └── IBM_HR_Analytics_Employee_Attrition.xlsx
│
├── Dashboard/
│   └── IBM_HR_Employee_Attrition_Dashboard.png
│
└── Documentation/
    └── IBM_HR_Analytics_Portfolio_Documentation.pdf
```

---

## Skills Demonstrated

* Excel Data Analysis
* Data Cleaning
* Data Validation
* XLOOKUP
* PivotTables
* PivotCharts
* KPI Development
* Dashboard Design
* Employee Attrition Analysis
* Workforce Segmentation
* Business Analysis
* Data Storytelling

---

## Conclusion

The analysis found an overall employee attrition rate of **16.12%** and identified notable patterns associated with overtime, work-life balance, job satisfaction, income level, departments, and job roles.

The findings suggest that employee retention is influenced by multiple workforce factors rather than a single variable.

This project demonstrates how Excel can be used to transform HR data into actionable business insights and support workforce retention decisions.
