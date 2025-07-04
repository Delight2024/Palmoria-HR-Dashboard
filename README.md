# Palmoria HR Gender Analyis Dashboard
## 1. Introduction
Human resource data holds the key to better decisions around compensation, diversity, performance, and compiance. This project focuses on transforming raw employee records into actionable HR insights through an interactive Power BI dashboard.

## 2. Project Topic
Gender and Compensation Analysis in Palmoria Group usin Power BI.

## 3. Project Overview
This dashboard analyzes Palmoria Group's workforce to identify:
-Gender distribution trends
-Salary gaps and pay bands
-Performance ratings by gender
-Bonus allocation across regions and departments
-Compliance with salary regulations
-
The goal is to support HR decision-making through clean visuals and data-driven recommendations.

## 4. Data Source
-Internal HR data (cleaned and merged)
-Final dataset used: 'Final_Employee_Data' (after Power Query Transformation)
-

## 5. Data Cleaning
-Removed employees without performance ratings from the dataset
-Replaced blank gender values with "Undisclosed" to ensure clarity and accuracy
-Removed rows with null values in key columns like 'Salary' and 'Rating'
-Cleaned and reformatted the 'Bonus Rules' table for consistent merging
-Merged the 'Employee Data' table with 'Bonus Rules' table in Power Query, while expanding and including only necessary fields
-Ensured appropriate data types:
  -'Salary', 'Bonus %', and 'Rating' as Decimal Numbers
  -'Department', Gender, and 'Location' as Text
-Created calculated columns in Power BI:
  -'Bonus_Amount' = Salary x Bonus %
  -'Total_Pay' = Salary + Bonus
  -'Pay_Band' = Grouped salary ranges (e.g., $20k-$30k); sorted using a lookup table ('PayBandFull') for correct order in visuals
  -

  ## 6. Exploratory Data Analysis (EDA) 
  The dashboard was organized  into three main analytical sections:
  ** 1. Workforce Composition**
  -Gender distribution overall
  -Gender breakdown by region and department
  -

  ** 2. Salary, Performance and Compliance**
  -Average and total salary comparison by gender
  -Performance ratings by gender
  -Compliance: count of employees earning below $90k
  -

  ** 3. Bonus & Compensation Insights**
  -Pay band distribution by region
  -Bonus amount and total pay comparison by region
  -Cards showing total company-wide bonus and total compensation
  -

  ## 7. Recommendations
  -Address salary disparities between male and female employees
  -Review bonus allocation across departments foe fairness
  -Investigate departments with skewed gender distribution
  -Continue monitoring compliance with pay regulations
  -

  ## 8. Conclusion
  This dashboard highlights the power of Power BI in transforming HR data into strategic insight. Palmoria can use this tool to ensure equitable compensation, strengthen compliance, and improve workforce planning.

  ---

  ### Palmoria HR Dashboard Preview
  ![Palmoria Dashboard Page 1](Palmoria%20Dashboard%20I.png)
  ![Palmoria Dashboard Page 2](Palmoria%20Dashboard%20II.png)

  ## Download Project File
  You can download the Power BI dashboard file here:
  ![Palmoria Group HR Dashboard.pbix](Palmoria%20Group%20HR%20Dashboard.pbix)
