\# HR Employee Attrition Analysis



\##  Project Overview

Employee attrition refers to the gradual reduction of an organization's workforce due to voluntary or involuntary departures. High attrition impacts productivity, increases recruitment and training costs, and leads to the loss of skilled talent.  

This project analyzes employee attrition using HR analytics to identify key drivers of turnover and provide actionable insights for workforce planning and retention strategies.

\##  Problem Statement

Organizations need to understand \*\*why employees leave\*\*.  

Attrition affects:

\- Productivity

\- Recruitment \& training costs

\- Loss of skilled talent  



The goal of this project is to \*\*identify key drivers of attrition\*\* using data analysis and provide insights to help HR improve retention.


\##  Tools \& Technologies

\- \*\*Python (Jupyter Notebook):\*\* Data cleaning, preprocessing, statistical analysis, and visualization  

\- \*\*Power BI:\*\* Interactive dashboards and visual storytelling for HR insights  

\- \*\*Libraries Used:\*\* Pandas, NumPy, Matplotlib, Seaborn  


\##  Dataset Description

\- \*\*Dataset:\*\* HR Employee Attrition  

\- \*\*Rows:\*\* 1,470  

\- \*\*Columns:\*\* 35  

\- \*\*Target Variable:\*\* Attrition  

\- \*\*Key Fields:\*\* Age, Department, Job Role, Monthly Income, Overtime, Job Satisfaction, Job Level, Years at Company, Salary Hike  


\##  Methodology

\### Step 1: Data Import \& Verification

\- Imported dataset into Jupyter Notebook using Pandas  

\- Verified dataset dimensions (1470 rows × 35 columns)  

\- Checked column names and data types  


\### Step 2: Data Cleaning

\- No missing values or duplicates  

\- Removed non-informative columns: `EmployeeCount`, `Over18`, `StandardHours`, `EmployeeNumber`  

\- Outlier detection using IQR and box plots (retained valid variations)  


\### Step 3: Exploratory Data Analysis (EDA)

\- Descriptive statistics (mean, median, min, max)  

\- Distribution analysis of Age, Monthly Income, Years at Company  

\- Attrition analysis by Department, Job Role, Salary, Overtime, Age, Tenure, Job Level  


\### Step 4: Visualization

\- \*\*Python (Matplotlib/Seaborn):\*\* Attrition trends, box plots, bar charts  

\- \*\*Power BI:\*\* Interactive dashboards showing attrition by department, age group, income levels, and overtime  


\### Step 5: Insights \& Interpretation

\- Attrition rate: \*\*16.1%\*\* (237 employees left)  

\- Highest attrition in \*\*Research \& Development\*\* and \*\*Sales\*\*  

\- \*\*Laboratory Technicians, Sales Executives, Research Scientists\*\* most affected  

\- \*\*Lower salaries, overtime, younger age (26–35), and <2 years tenure\*\* strongly linked to attrition  

\- Entry-level employees (Level 1) most likely to leave 



\## Conclusion

Employee attrition is influenced by multiple factors:

\- Salary  

\- Overtime  

\- Age group  

\- Job satisfaction  

\- Tenure  

\- Job level  


HR analytics enables organizations to make \*\*data-driven decisions\*\* to improve retention.



\## Suggestions

To reduce attrition, organizations should:

\- Ensure fair pay across job levels and roles  

\- Offer competitive compensation and performance-based rewards  

\- Provide additional allowances for overtime work  

\- Strengthen retention strategies for entry-level employees  

\- Recognize and appreciate employees to maintain workplace harmony  

## Business Recommendations

**Target retention efforts at Research & Development and Sales**, the two departments with highest attrition, rather than applying a flat company-wide policy.
  
**Review compensation specifically for Laboratory Technicians, Sales Executives, and Research Scientists**, since these roles show disproportionate attrition — a role-specific pay-benchmarking exercise could identify the gap.

**Redesign overtime policy**, since overtime is strongly linked to attrition — consider overtime caps or additional compensation for sustained overtime.

**Build a 90-day and 1-year retention program for entry-level (Level 1) hires**, since tenure under 2 years and younger age groups (26-35) show the highest flight risk — early mentorship or check-ins could reduce early attrition.
