# Customer Churn Analysis

## Overview

Customer Churn Analysis is a data analytics project that explores customer attrition patterns in the banking sector using Python. Through Exploratory Data Analysis (EDA), the project identifies demographic, behavioral, and financial factors associated with customer churn, helping businesses understand customer retention challenges and make data-driven decisions.

## Project Objective

The objective of this project is to analyze customer data and uncover the key factors influencing churn. By identifying high-risk customer segments, banks can develop targeted retention strategies and improve customer satisfaction.

## Dataset Information

**Dataset:** Bank_Churn.csv

### Features
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited (Target Variable)
  - 1 = Customer Churned
  - 0 = Customer Retained

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis Performed

### Data Preparation
- Loaded and explored the dataset
- Checked data types and missing values
- Cleaned the dataset for analysis

### Exploratory Data Analysis
- Analyzed customer churn distribution
- Examined demographic factors such as age, gender, and geography
- Investigated customer behavior including tenure, activity status, and product usage
- Evaluated financial indicators such as credit score, account balance, and estimated salary
- Generated correlation matrix and Pearson correlation analysis

## Visualizations

- Bar Charts
- Pie Charts
- Histograms
- Count Plots
- Box Plots

## Key Insights

- Customers aged above 40 showed a higher probability of churn.
- Inactive customers were significantly more likely to leave the bank.
- Geography played a notable role in churn behavior, with certain regions exhibiting higher attrition rates.
- Customers with higher account balances demonstrated increased churn tendencies.
- Product ownership and customer tenure showed meaningful relationships with retention.
- Credit score and estimated salary had relatively weak influence on churn outcomes.
- Customer engagement metrics were stronger churn indicators than financial attributes.

## Conclusion

This analysis identified key factors associated with customer churn, particularly customer activity level, age, product usage, tenure, and account balance. The findings can help banking institutions design targeted retention strategies, improve customer engagement, and reduce customer attrition through data-driven decision-making.
