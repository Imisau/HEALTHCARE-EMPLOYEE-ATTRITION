# Healthcare Employee Attrition And Retention
![](https://github.com/Imisau/HEALTHCARE-EMPLOYEE-ATTRITION/blob/main/PBI_IMAGE.png?raw=true)

## Introduction
This a Power BI project that shows key patterns behind employee attrition by looking at demographics, income, tenure, job roles, overtime, promotions, and manager relationships. Most attrition comes from employees aged 30–39, earning $1K–$5K monthly, working overtime, and having short tenures. Understanding these trends can help HR create better retention strategies and keep skilled workers in the organization.

## Problem Statement
A healthcare organization has collected extensive data on it employees across various department and seeks to leverage this data to make inform decisions.
There is a need to identify the factors contributing to the issue of attrition and develop strategies to improve employee retention and job satisfaction.

## Process
Cleaned data was downloaded onto local storage and then connected a MySQL workbench for analysis. This include using GROUP BY clause or CASE WHEN statement to calculate aggregate attrition rates base on employee factors other factor like role, department, income, and years with the company. All insight translated to a user friendly visual made in Power BI. Other Functions are used to transform data using DAX and Power Query in Power BI. Data validations, evaluations, predictions and statistical operations are performed using Excel and Jupyter Notebook, using Pandas and Numpy 

## Demographics & Employment
![](https://github.com/Imisau/HEALTHCARE-EMPLOYEE-ATTRITION/blob/main/PBI_DEMO_EMPLOY.png?raw=true)

## Statistical Factors From Prediction Model:
-	Our attrition prediction model identified several statistically significant risk factors that correlate strongly with higher likelihood of employee turnover
- Frequent Overtime (38% higher risk)
- Low Job Involvement (32% higher risk)
- Younger Age who are less than 30 years (27% higher risk)
- Single Marital Status (25% higher risk)
- Few Years with Current Manager (22% higher risk)
- No Recent Promotion (18% higher risk)
- Multiple Previous Employers (16% higher risk)
- (All percentages scaled to a 100% model weight benchmark.)

## Attrition Analysis Dashboard
![](https://github.com/Imisau/HEALTHCARE-EMPLOYEE-ATTRITION/blob/main/PBI_ANALYTIC%20_DASHBOARD.png?raw=true)

## Summary of Findings & Predictions
- Frequent Overtime: Suggests workload imbalance, possible burnout, or poor work-life balance.
- Low Job Involvement: Indicates disengagement and lack of emotional connection to role.
-	Younger Employees: More likely to explore opportunities or feel underdeveloped.
-	Single Employees: May have higher mobility and fewer anchor points.
-	Short Tenure with Manager: Lack of relationship stability or mentorship.
-	No Recent Promotion: Indicates career stagnation and potential dissatisfaction.
-	High Job History Volatility: May reflect low organizational loyalty.


## Recommendations
-	Work-Life Balance Initiative; Audit departments with frequent overtime.
-	Implement flexible hours or time-off incentives. 
-	Job Engagement Programs; Deploy pulse surveys to measure engagement. Recognize and reward proactive contributions. 
-	Targeted Retention for Young Talent; Offer career development paths and mentorship. 
-	Create early-career leadership training. 
-	Career Progression Monitoring; Flag employees without promotion in 2+ years. Implement career review sessions.
-	Manager-Employee Bonding; Support 1:1s and check-ins for new manager reports. Offer manager coaching programs.
