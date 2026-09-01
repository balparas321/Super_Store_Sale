# Superstore Sales – Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on Superstore sales data using Python to uncover meaningful patterns in sales, profit, customers, discounts, shipping performance, and product-related business metrics.

The analysis focuses not only on visualization but also on data quality, preprocessing, feature engineering, and business-oriented insights.

## Key Analysis Performed

- Cleaned and validated the dataset by handling duplicate records, missing values, inconsistent dates, and data formatting issues.
- Converted date columns into appropriate datetime format and corrected inconsistencies between 'Order ID' and 'Order Date' years.
- Calculated shipping duration and analyzed shipping modes based on delivery time.
- Handled missing values in the Quantity column using statistical analysis.
- Removed customer names to maintain privacy and created a masked customer identifier.
- Standardized state names and postal-code formatting.

- Performed feature engineering to derive:
  - Original Price
  - Total Sales
  - Total Profit
  - Discount Price
  - Total Discount
  - Shipping Urgency
  - Days Since Last Order
  
- Performed customer-level analysis of sales, quantity, and discounts.
- Identified and analyzed outliers using statistical and visualization techniques.
- Analyzed relationships between shipping modes, regions, sales, and profitability.
- Used pivot tables and aggregations to compare business performance across different dimensions.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Objective

The primary objective of this project is to transform raw sales data into meaningful insights by applying data cleaning, statistical analysis, feature engineering, and visualization techniques.
