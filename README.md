# Sales Analysis of AtliQ 
## Objective : 
Atliq is selling hardware and peripheral to other states and region , scope of the project is to identify the sales trend in the market by analyze historical sales patterns and create a interactive dashboard, reports using PowerBI, enabling stakeholders to gain actionable insights at a glance. 
## Problem Statement :
Sales manger states that sales are being declined for this year and what to know the zone-wise performance report. They need a detailed report and dashboard to track the sales trends in each states and analyze the markets.
## Project Overview : 
Dataset consists of 5 tables and sales data ranges from 2017 to 2020
- **1]** Customers — customer_code, custmer_name, customer_type.
- **2]** Date — date, cy_date, year, month_name, date_yy_mmm.
- **3]** Markets — markets_code, markets_name, zone.
- **4]** Products — product_code, product_type.
- **5]** Transactions — product_code, customer_code, market_code, order_date, sales_qty, sales_amount, currency.
## Steps Involved : 
#### Data Analysis using MySQL
Connected and import data in Mysql database and work on raw data, executed SQL commands.
### Data Cleaning and ETL(Extract, Transform, & Load)
       - Cleaning the dataset with unnecassary and duplicate records
       - Formating the currency to INR in Power Query Editor 
       - Filter the required attribute in all the tables and formating the data types of the columns
       - Building relationship between tables using Data Modeling and connecting the primary key with attributes
### Creating Report in PowerBI
   Visualizaing the data with different charts to analysis the pattern and trends in markets and working on DAX measures will provide more details insights to the stakeholders 

## Overview of key sales metrics:
- 75% of the customer contribute to Brick & mortor and 25% to E-commerce.
- South zone region sell the product with 5.81% profit margin and 16% quantity,central contributes 31% in quantity and 3.25% for profit margin followed by North 2.23% profit margin and 52% Quantity 
- Total quantity of products sold amounts to 2.43 million (M).
- The YoY sales growth stands at 142.22 million (M), representing a negative deviation of 57.67% from the target of 336.02 million (M). 



