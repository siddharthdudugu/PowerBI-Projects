# Credit Card Default Analysis in Power BI
## Overview
This project involves the analysis of a USA credit card defaulter dataset using Power BI. The goal is to identify patterns and insights related to credit card defaults based on various demographic and financial factors. The dataset includes information about customers such as their credit limit, age, gender, education, marital status, payment history, and billing amounts.

## Dataset Description
The dataset contains the following columns:

- ID: Customer ID
- LIMIT_BAL: Credit limit balance
- SEX: Gender of the customer (1 = male, 2 = female)
- EDUCATION: Education level (1 = graduate school, 2 = university, 3 = high school, 4 = others)
- MARRIAGE: Marital status (1 = married, 2 = single, 3 = others)
- AGE: Age of the customer
- PAY_0 to PAY_6: Payment status from the last six months (e.g., -1 = pay duly, 1 = payment delay for one month, 2 = payment delay for two months, etc.)
- BILL_AMT1 to BILL_AMT6: Bill statement amounts from the last six months
- PAY_AMT1 to PAY_AMT6: Payment amounts from the last six months
- Y: Default payment next month (1 = yes, 0 = no)
- state: State of residence

## Power BI Report Description
The Power BI report provides a comprehensive analysis of credit card defaults, presented through various visualizations and metrics:

Defaulted by Education Level and Gender:

A bar chart showing the number of defaulters categorized by education level and gender.
Defaulted by Age and Gender:

A line chart depicting the number of defaulters across different age groups for both genders.
Defaulted by Gender:

A bar chart comparing the number of male and female defaulters.
Defaulted by Marital Status and Gender:

A bar chart showing defaulters categorized by marital status and gender.
Defaulted by State:

A filled map illustrating the default rates across different states in the USA.
## Key Metrics:

- Default Rate: The overall default rate.
- Latest Average Pay Amount: The average payment amount for the latest month.
- Latest Average Bill Amount: The average bill amount for the latest month.
## Analysis Summary
The analysis provides valuable insights into the demographic and financial characteristics of credit card defaulters:

- Education Level: Higher education levels tend to have fewer defaulters.
- Age and Gender: Younger age groups, particularly those in their 20s and 30s, show higher default rates. Males have slightly higher default rates compared to females.
- Marital Status: Single individuals have a higher default rate compared to married individuals.
- State-wise Analysis: Some states have higher default rates, indicating potential regional economic influences.
## Conclusion
The Power BI report effectively highlights the key factors influencing credit card defaults, allowing stakeholders to make informed decisions and develop targeted strategies for mitigating default risks. This analysis can help financial institutions better understand their customer base and improve credit risk management practices.
