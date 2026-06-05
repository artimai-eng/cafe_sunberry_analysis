# Cafe Sunberry Sales and Revenue Analysis

## Project Overview 
Cafe Sunberry Sales and Revenue Analysis is an attempt to solve business problems and also understand them in a deeper level, such as understanding customer purchasing behaviour, product performance, sales trend and the data quality

The objective of this project is to identify opportunities to increase revenue, improve product performance, and support business decision-making through data-driven insights.

## Business Problem 

Cafe owners often dont know the answers to questions such as :
- Which products generate the highest revenue?
- Which products are popular but underperforming financially?
- Which days and months contribute most to sales?
- How do customers prefer to pay?
- Are there operational issues affecting data quality?

This project aims to answer these questions using transaction-level sales data.

## Dataset information

The dataset contains approximately 10k transaction records, attributes being :- 
 - Item Purchased
 - Quantity
 - Price Per Unit
 - Total Spent
 - Payment Method
 - Location (Takeaway / In-Store)
 - Transaction Date
Day and Month are later extracted from Transaction Date.

Approximately 8% of records contained missing values or incomplete information

# Data Cleaning Process
## Challenges Identified
 - Missing transaction values
 - Blank entries
 - Unknown values
 - System-generated errors
  
## Cleaning Actions Performed
Reconstructed missing values using transaction logic:
  -  Total Spent = Quantity × Price Per Unit
  -  Quantity = Total Spent ÷ Price Per Unit
  -  Price Per Unit = Total Spent ÷ Quantity
Preserved error records to evaluate the impact of poor data collection on business decisions.

# Dashboard Features

The dashboard includes:

 - Revenue vs Quantity Sold Analysis
 - Weekly Revenue Trends
 - Monthly Revenue Trends
 - Payment Method Distribution
 - Location Analysis (Takeaway vs In-Store)
 - Location vs Payment Method Analysis

Interactive slicers allow filtering by:

  - Item
  - Month
  - Payment Method
  - Location

  ------------------------------------------------------------------
  # Key Insights 

  ## Product Performance 
  
 - Salad,Smoothies,Sandwich,juice are the most revenue generating items.
 - While Cookie (one of the most ordered) and Tea are the least revenue generating item.
 - Coffee is the highest ordered item yet not contributing much to the revenue.
 - The Highest AOV is of salad followed by sandwich and smoothie.

## Weekly Analysis

-  Sunday,Monday,Thurday are the highest performing days in a week.
-  Wednesdays are the least productive day.
-  Lower sales of high-revenue products like juice and cake contributed to Wednesday's decline

## Monthly analysis

-  January,March and June were the most productive months.
-  February being the least.
-  A decline in Feb's sales were due to the lowest sale of Sandwich(high revenue generator) across all months.

## Customer analysis

-  Digital Wallets was the most preffered mode of overall payment by 23%.
-  Customers prefer in-store by a whooping 31% compared to takeway(29%)
-  People preferred to pay by cash than Digital wallets more in in-place orders and vice versa for takeaway.
  
## Data Quality Findings
 - Approximately 32% of payment records contained errors.
 - Approximately 40% of location records contained errors.

These data quality issues reduce the reliability of business insights and highlight the need for better operational processes.

# Business Recoomendations 

- Bundle low-revenue products such as cookies and tea with higher- performing products.
- Introduce combo offer.
- Improve the data collection system to increase accuracy and effeciency.
- Promote more high- revenue items on Wednesdays.

# Tools Used 
*  Microsoft Excel 
* Pivot Tables
* Pivot Charts
*  Dashboard Design
*  Data Cleaning
*  Business Analytics

# Project Outcome

This project demonstrates how transaction-level sales data can be transformed into actionable business insights that support revenue growth, operational improvements, and strategic decision-making.
