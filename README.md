# HR Analysis-Dashboard

Problem Statement
The HR Analysis Dashboard uncovers factors driving employee attrition and provides insights into key aspects of employee satisfaction and involvement. This dashboard allows HR teams to explore critical questions like "What is the distribution of attrition by job role and distance from home?" or "How does the average monthly income compare across education levels for those who stay versus those who leave?" Leveraging a fictional dataset created by IBM data scientists, this analysis supports strategic decision-making for employee retention.

Objectives of the Analysis
Understand Current Turnover Rates: Obtain a detailed view of the employee turnover rate, breaking down attrition by demographics such as age, gender, education, department, and job role.

Identify Key Factors Influencing Turnover: Analyze primary factors contributing to attrition, such as job satisfaction metrics (job involvement and work-life balance), income (monthly salary and raises), and benefits (stock options), to reveal patterns that influence higher attrition.

Dataset Details
Education Levels:

1: Below College
2: College
3: Bachelor
4: Master
5: Doctorate

Environment Satisfaction:

1: Low
2: Medium
3: High
4: Very High

Job Involvement:

1: Low
2: Medium
3: High
4: Very High

Job Satisfaction:

1: Low
2: Medium
3: High
4: Very High

Performance Rating:

1: Low
2: Good
3: Excellent
4: Outstanding

Relationship Satisfaction:

1: Low
2: Medium
3: High
4: Very High

Work-Life Balance:

1: Bad
2: Good
3: Better
4: Best

### Steps followed 

1. Data Cleaning: Removed or addressed null values in relevant fields for accurate calculations and visualizations using python

2. Data Loading: Loaded the dataset (CSV file) into Power BI Desktop.

3. Attrition Rate Calculation: Created a calculated column called "Attrition Rate" that divides the sum of attrition count by the total number of employees, enabling classification of each factor based on attrition rate.

4. Data Transformation: Added new columns to create groups or bins for "Age," "Education," "Environment Satisfaction," and "Job Satisfaction" to enable accurate classification and facilitate detailed analysis.

5. Theme Selection: Selected a cohesive theme in Report View for a visually consistent dashboard.

6. Key Metrics and KPIs: Added visuals for Total Attrition Rate, and total number of male and female employees.

7. Attrition by Demographics: Created visual filters (slicers) for fields like "Education," "Department," and "Job Role" to facilitate targeted analysis.
 
8. Segmented metrics by factors like department and role to pinpoint areas with low satisfaction.

9. Income Analysis: Added bargraph for visualizing attrition rate based on percent of salary hike.

# Snapshot of Dashboard (Power BI)

![dashboard_snapo](https://github.com/Nihal023251/HR-analytics/blob/main/HRDashboard.PNG?raw=true)


# Insights

Following inferences can be drawn from the dashboard;

### [1] Total Number of Employees = 1470

   Number of Employees (Male) =  882

   Number of Employees (Female) =  588

   Total Attrition Rate = 16.12%

           
### [2] Attrition Rate based on Gender

   Attrition Rate for Male Employees = 17.01%

   Attrition Rate for Female Employees = 14.80%

      Thus Attrition is slightly higher among male employees.
    
  
### [3] Attrition Rate based on Age Groups 
  
   Attrition Rate is very high among Young Employees and it decreases by age.

### [4] Attrition Rate based on Education 
 
   Employees with education level 'below college' has most number of attrition rate

   Employees with education catgeory level 'doctor' has lower rate of attrition

### [6] Attrition Rate based on Salary Hike

   Attrition rate based on salary hike is not an area of concern since there was not much of a noticable difference based on the percent of salary hike employees received

### [6] Attrition Rate based on Deparment and Job Role

   Employees from Sales and HR Department has higher attrition rate over 20% and 19% respectively

   Employees with the JobRole of Sales Representative from the Sales Department has the highest rate of attrition reaching almost 40%
  

