# Pizza-Sales-Analysis-Dashboard

### Project Overview

Welcome to the Pizza Sales Analysis project! This repository contains an Excel-based analysis of pizza sales data, providing valuable insights into sales patterns, customer preferences, and product performance. This project is designed to help understand various aspects of pizza sales, from daily and hourly trends to the popularity of different pizza categories and sizes.

### Data Sources

Sales Data: The primary dataset used for this analysis is the "Pizza_sales.csv" file, containing detailed information about each sale made by the company.

### Tools

 - Excel - Data cleaning and visualization
 - SQL Server - Data Analysis

### Data Cleaning

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data Cleaning and formatting

### Exploratory Data analysis

EDA involved exploring the sales data to answer key questions, such as:
1. What is the total Revenue?
2. What is the average order value?
3. Total pizza sold?
4. Total orders?
5. Average pizzas per order?
6. Daily trends?
7. Hourly trends?
8. Percentage of sales by pizza category?
9. Percentage of sales by pizza size?
10. Total pizzas sold by pizza category?
11. Top 5 best sellers by total pizzas sold?
12. Bottom 5 pizzas sold?

### Data analysis

Include some interesting code/features worked with

```sql
select datename(DW,order_date) as order_day, count(distinct order_id) as total_orders
from pizza_sales
group by datename(DW,order_date);
```
### Results/Findings

The analysis results are summarized as follows:
1. Orders are highest on weekends, friday/saturday evenings. There are maximum orders from 12-01 pm  and after 4-8 pm.
2.              CATEGORY
 Classic category contribute
 to maximum sales and total 
               orders.

                  SIZE
 Large pizza size contribute to  maximum sales.

   







