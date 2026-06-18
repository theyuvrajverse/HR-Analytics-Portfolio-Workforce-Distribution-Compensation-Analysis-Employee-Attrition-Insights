# HR-Analytics-Portfolio-Workforce-Distribution-Compensation-Analysis-Employee-Attrition-Insights
HR Analytics Portfolio | SQL, Power BI &amp; Tableau projects covering workforce demographics, salary analysis, employee distribution, attrition insights, and business intelligence reporting.
# HR Analytics Portfolio (SQL, Power BI & Tableau)

## Project Overview

A collection of HR analytics projects covering workforce analysis, employee distribution, compensation trends, and attrition insights using SQL, Power BI, and Tableau.

**Note:** The SQL exercises, Power BI dashboard, and Tableau dashboard were built using separate HR datasets. They are grouped together as an HR Analytics portfolio demonstrating database querying, workforce reporting, and employee attrition analysis.

---

## SQL Analytics: Employee & Department Analysis

### Business Problem

Organizations need efficient methods to analyze employee performance, compensation, departmental structure, and workforce distribution. This SQL project focuses on solving common HR business questions through advanced querying techniques.

### Database Structure

Analyzed employee and department data using relational database concepts and SQL query optimization techniques.

### SQL Analysis

Developed 55 SQL queries covering:

* Joins (Inner, Left, Right, Self Join)
* Correlated Subqueries
* EXISTS and NOT EXISTS clauses
* ANY and ALL operators
* Aggregate functions and grouping
* CASE-based employee classification
* Salary benchmarking and comparison analysis

### Key Insights

* Identified employees earning above and below departmental salary averages.
* Classified employees into performance and compensation categories using CASE statements.
* Detected departments with higher-than-average salary expenditure.
* Analyzed employee-to-department relationships through advanced joins and subqueries.
* Demonstrated multiple approaches for solving business reporting questions using SQL.

---

## Power BI Dashboard: Workforce Distribution Analysis

### Business Problem

HR teams require visibility into workforce demographics, compensation distribution, and organizational structure to support workforce planning and diversity initiatives.

### Dashboard Metrics

* Total Employees: 1,480
* Male Employees: 889
* Female Employees: 591
* Total Monthly Income:

  * Male Employees: $5.7M
  * Female Employees: $4.0M

### Key Findings

* Male employees represented approximately 60% of the workforce.
* Female employees accounted for approximately 40% of total headcount.
* Male employees generated higher aggregate monthly income than female employees, indicating a compensation gap that warrants deeper investigation by role, experience, and tenure.
* Life Sciences was the largest education field, representing 607 employees.
* One department accounted for 39.66% of total workforce concentration, highlighting a significant staffing imbalance across departments.

### Business Recommendations

* Conduct compensation equity analysis across roles and experience levels.
* Evaluate workforce diversification opportunities within heavily concentrated departments.
* Review recruitment strategies to improve workforce balance across educational backgrounds and functions.

---

## Tableau Dashboard: Employee Attrition Analysis

### Business Problem

Employee turnover creates recruitment costs, productivity loss, and organizational disruption. The objective was to identify attrition trends and workforce segments at higher risk of leaving.

### Dashboard Metrics

* Total Employees: 1,470
* Employees Leaving: 237
* Attrition Rate: 16%

### Key Findings

* Overall employee attrition stood at 16%.
* Sales Executive and Laboratory Technician positions experienced the highest attrition counts.
* Employees aged 29–34 accounted for 29.11% of total attrition, making early-to-mid-career professionals the most vulnerable segment.
* Attrition patterns varied significantly across job roles and demographic groups.
* Workforce retention challenges were concentrated within specific functions rather than evenly distributed across the organization.

### Business Recommendations

* Develop targeted retention programs for high-attrition roles.
* Implement career progression initiatives for employees in the 29–34 age group.
* Conduct exit-interview analysis to identify root causes behind turnover patterns.
* Prioritize employee engagement efforts in departments with elevated attrition levels.

---

## Files

* `hr_subquery_practice.sql` — Advanced SQL queries, joins, subqueries, and business analysis exercises
* `workforce_distribution_dashboard.pbix` — Power BI workforce analytics dashboard
* `attrition_dashboard.twbx` — Tableau employee attrition dashboard

## Tools & Technologies

* MySQL
* Power BI
* Tableau Public
* SQL Joins & Subqueries
* DAX
* Data Modeling
* Workforce Analytics
* Attrition Analysis
