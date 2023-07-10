
# 🛒 Case Study #5 - Data Mart



![Logo](https://8weeksqlchallenge.com/images/case-study-designs/5.png)


## 📕 Table of Contents

 - Bussiness Task
 - Entity Relationship Diagram
 - Case Study Questions
 - My Solution

## 🛠️ Bussiness Task

Data Mart is an online supermarket that specialises in fresh produce. In June 2020 - large scale supply changes were made at Data Mart. All Data Mart products now use sustainable packaging methods in every single step from the farm all the way to the customer.

Danny needs your help to analyse and quantify the impact of this change on the sales performance for Data Mart and it’s separate business areas. The key business question to answer are the following:

   - What was the quantifiable impact of the changes introduced in June 2020?

   - Which platform, region, segment and customer types were the most impacted by this change?

   - What can we do about future introduction of similar sustainability updates to the business to minimise impact on sales?


## 🔐 Entity Relationship Diagram

![Logo](https://github.com/sameer8765/8-Week-SQL-Challenge/blob/main/Case%20Study%20%235%20-%20Data%20Mart/e5.png?raw=true)

## ❓ Case Study Questions

A. Data Cleansing Steps

In a single query, perform the following operations and generate a new table in the data_mart schema named clean_weekly_sales:

   - Convert the week_date to a DATE format

   - Add a week_number as the second column for each week_date value, for example any value from the 1st of January to 7th of January will be 1, 8th to 14th will be 2 etc

   - Add a month_number with the calendar month for each week_date value as the 3rd column

   - Add a calendar_year column as the 4th column containing either 2018, 2019 or 2020 values

   - Add a new column called age_band after the original segment column using the following mapping on the number inside the segment value

   - Add a new demographic column using the following mapping for the first letter in the segment values

   - Ensure all null string values with an "unknown" string value in the original segment column as well as the new age_band and demographic columns

   - Generate a new avg_transaction column as the sales value divided by transactions rounded to 2 decimal places for each record

B. Data Exploration

   - What day of the week is used for each week_date value?

   - What range of week numbers are missing from the dataset?

   - How many total transactions were there for each year in the dataset?

   - What is the total sales for each region for each month?

   - What is the total count of transactions for each platform

   - What is the percentage of sales for Retail vs Shopify for each month?

   - What is the percentage of sales by demographic for each year in the dataset?

   - Which age_band and demographic values contribute the most to Retail sales?

   - Can we use the avg_transaction column to find the average transaction size for each year for Retail vs Shopify? If not - how would you calculate it instead?


  
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_solution-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/sameer8765/8-Week-SQL-Challenge/blob/main/Case%20Study%20%235%20-%20Data%20Mart/SQL%20query)

