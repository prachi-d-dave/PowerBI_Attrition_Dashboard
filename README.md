# Attrition Dashboard

## Dataset Overview

This dataset contains 38 columns and 1,480 rows. This data includes information about employees like Employee ID, Age, Attrition, Monthly Income, Department, Total Years at Company, Salary Hike Percentage, Years with Current Manager, Environment Satisfaction, Overtime, Martial Status, etc.
Looking at the dataset we get to know that total number of employees are 1,470 and total attrition count is 237 which is 16.21%.

## Project Overview

This dashboard provides insights to the organization to understand their attrition better. It aids the organization specifically HR department have knowledge of secondary responsible factors that affect attrition other than some obvious factors like age, salary, education and job satisfaction. Through different visualizations they get a deeper understanding thus, making it easy for them to take measures of retention.

## Project Objective

1.	Identify KPIs and design an intuitive and visually appealing dashboard

2.	Add interactive visualizations and filtering capabilities to allow users to explore the data at various levels of granularity


3.	Conduct data analysis to provide valuable insights to organization regarding the secondary areas of attrition happening at deeper level

4.	End goal is to share valuable insights and actionable information that can drive strategic decision-making and support measures to be applied for retention of employees

## Steps followed 

- Step 1 : Explored the Dataset using MS Excel, converted CSV file into Excel format for this step
- Step 2 : Added column ‘Salary Slab’ & ‘Age Group’ for better analysis 
- Step 3 : Identified underlying responsible factors and KPIs
- Step 4 : Loaded the dataset in Power BI, dataset is CSV file
- Step 5 : Data Cleaning & Processing in Power Query – Identified ‘Null Values’ and ‘Duplicate Values’ were removed
- Step 6 : Data Cleaning & Processing in Power Query – Replaced values to have uniformity and detected ‘Data Types’ to have accuracy in dataset
- Step 7 : Data Cleaning & Processing in Power Query – Used ‘DAX Query’ to create custom calculated column for creating columns like ‘Attrition Count’ and ‘Performance Rating’  
- Step 8 : Built related KPIs 
- Step 9 : Built the visualizations using suitable charts 
- Step 10 : Built slicers for easy access to important filters 
- Step 11 : Our Dashboard is ready

## Inferences

### [1] Our KPIs
The four KPI are ‘Total Attrition’, ‘Average Hike Percent’, ‘Major Rating’ and ‘Average Salary’ which are 237 attritions, 15.21%, 1 Rating and 6.5K salary representing respectively.

### [2] Attrition by Salary Hike Percent
This Line Chart shows that the most employees who left the organization got 11% to 15% hike in salary. To highlight the highest number are: 41 employees got 11%, 34 employees got 13% and 24 employees got 14%.
           
### [3] Attrition by Job Role
This clustered chart helps us clearly understand that out of many job roles the top four roles where attrition happens most are: ‘Laboratory Technician’, ‘Sales Executive’, ‘Research Scientist’ and ‘Sales Representative’. Where ‘Laboratory Technician’ are 62 and ‘Sales Representative’ are 33.
  
  ### [4] Attrition by Job Level
Each employee has been given job level number from 1 to 5 where 1 comprises of starting level position like ‘Sales Representative’ and 5 comprises of top-level position like ‘Manager’.
The Stacked Column Chart compares attrition count of each of the job level. The chart portrays that most attrition happens at level no. 1 which is 143 and least happens at level no. 4 and 5 which is 5.

 ### [5] Attrition by Performance Rating
Pie chart represents that people having 1 as performance rating are highest to leave the organization which is 37% followed by people having 2 as performance rating which is 35%. Only 5% of employees left the company having 5 as the rating.

### [6] Attrition by Years Since Last Promotion

Stacked area chart helps us get deeper insight of attrition count by years passed since last promotion. Between 0 to 2 years since promotion we can see the most attrition happening being 110 to 27 respectively. After this period, we can see that as 7 years are completed since promotion again there is spike in attrition being 16.

### [7] Slicers
We have two slicers to filter are visualizations to get deeper understanding. One is ‘Salary Slab’ and another is ‘Gender’. If we consider the field of these slicers then salary under ‘Below 5k’ and ‘Male’ gender are comparatively to have higher attrition.
 
All the visualizations will change accordingly if different visual filters will be applied. 
