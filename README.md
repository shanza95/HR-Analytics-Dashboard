  
# HR ANALYTICS - EMPLOYEE ATTRITION

## Dashboard Overview

This dashboard provides a comprehensive analysis of employee attrition across the organization. Attrition indicates whether an employee has left the company (“Yes”) or is currently employed (“No”).
The objective is to help HR teams identify key trends, risk areas, and opportunities to improve employee retention and workforce planning.

![Dashboard%20screenshort](Dashboard%20screenshort.png/)

To explore the fully interactive and dynamic version—where all charts update automatically based on your selections—please access the live dashboard [here](https://public.tableau.com/app/profile/shanza.saleem/viz/HRAnalyticsDashboard_17529301205440/HRAnalyticsDashboard).

## Report Summary

This report highlights detailed insights into attrition patterns, workforce demographics, job satisfaction, and department-level impacts. It includes key metrics such as total employee count, attrition count, attrition rate, age distribution, and satisfaction scores.

### Key Metrics/ Kpi's Definitions

| Metric / Field           | Description                                                                      |
| ------------------------ | -------------------------------------------------------------------------------- |
| **Attrition Definition** | **Yes** → Employee has left the company <br> **No** → Employee is still employed |
| **Total Employee Count** | Total number of employees included in the dataset.                               |
| **Attrition Count**      | Total number of employees marked as **“Yes”** (employees who left).              |
| **Attrition Rate**       | `SUM(Attrition Count) / SUM(Employee Count)`                                     |
| **Active Employees**     | `SUM(Employee Count) - SUM(Attrition Count)`                                     |
| **Average Age**          | Mean age of employees across the organization.                                   |


## Key Findings from the HR Analytics Dashboard

### 1. Workforce Overview
- Total employees: 1,470
- Active employees: 1,233
- Attrition count: 237
- Attrition rate: 16.12%, indicating above-average turnover
- Average workforce age: 37, reflecting a predominantly mid-career employee base

### 2. Attrition Patterns

- *By Gender*
  
  -   Male attrition (150) is noticeably higher than female attrition (87).
  -   Indicates potential differences in job roles, work conditions, or retention drivers.

- *By Department*
  
  -   R&D shows the highest attrition (56%), suggesting challenges related to workload, industry competition, or job expectations.
  -   Sales and HR display lower attrition levels.

- *By Age Group*
  
  -   Highest attrition occurs among employees aged 25–34, followed by 35–44.
  -   Younger employees (<25) show moderate turnover
  -   older groups (45+) display much lower attrition.

This trend aligns with career mobility patterns—mid-career employees may be more likely to switch jobs.

### 3. Job Satisfaction Insights
*Satisfaction ratings range from 1 to 4 (4 = highest).*

- Roles such as Laboratory Technicians and Sales Executives show heavier clustering in mid-range satisfaction levels.
- Roles with lower satisfaction tend to align with higher attrition.
  
### 4. Education-Level Impact

- Noticeable attrition among employees with:

  -   Life Sciences backgrounds
  -   Medical backgrounds
  -   Marketing backgrounds

It suggests higher competition and external demand in specialized fields.

### 5. Workforce Demographics

Most employees fall between ages 26–36, forming the largest portion of the workforce.
This aligns with the fact that mid-career groups also show the highest attrition.

## Overall Interpretation

The analysis reveals a concentrated attrition challenge among mid-career employees, particularly within the R&D department and among male employees.
Patterns in satisfaction levels, age distribution, and educational background suggest opportunities to strengthen retention strategies through:

- Improved employee engagement initiatives
- Career development programs
- Department-specific workload or expectation adjustments
- Targeted support for high-attrition roles and demographics

### APPENDICES
- Data Source: Kaggle
- Visualization Tools: Tableau


