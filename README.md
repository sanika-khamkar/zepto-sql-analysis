# Zepto Product Analysis using MySQL

## Project Overview

This project analyzes Zepto product data using MySQL. The objective is to perform data cleaning, exploratory data analysis (EDA), and generate business insights from product pricing, discounts, inventory, and category performance.

## Dataset Information

* Total Records: 3,731
* Categories: 14
* Source: Zepto Product Dataset

## Data Cleaning

* Removed records with invalid prices.
* Converted product prices from paise to rupees.
* Validated null values across all columns.
* Verified stock availability status.

## Key Analysis Performed

1. Product Count Analysis
2. Category-wise Product Distribution
3. Stock vs Out-of-Stock Analysis
4. Duplicate Product Detection
5. Best Value Products (Price per Gram)
6. Weight Category Classification
7. Inventory Weight Analysis
8. Highest Discount Products
9. High MRP Out-of-Stock Products
10. Category-wise Revenue Estimation
11. Average Discount Analysis

## SQL Concepts Used

* SELECT
* WHERE
* GROUP BY
* HAVING
* ORDER BY
* CASE
* Aggregate Functions
* Data Cleaning Queries
* Data Import using LOAD DATA INFILE

## Key Insights

* Fruits & Vegetables offered the highest average discounts.
* 453 products were out of stock.
* Several products had discount rates above 50%.
* Inventory and pricing patterns varied significantly across categories.

## Tools

* MySQL
* Excel
