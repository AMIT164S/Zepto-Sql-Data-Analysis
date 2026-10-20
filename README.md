# Zepto SQL Data Analysis Project

## Project Overview
In this I worked with an original Zepto product dataset sourced from Kaggle. I used SQL and PostgreSQL to explore the data and understand product pricing, discounts, stock availability, and inventory across different categories.

Through this project, I got practical experience working with a real-world dataset and using SQL to answer different business-related questions.

## Project Objectives
- Explore the dataset and understand its structure.
- Check for missing values and identify products with zero prices.
- Find product names that appear multiple times.
- Analyze product prices and discount percentages.
- Compare products that are in stock and out of stock.
- Calculate estimated inventory value for different categories.
- Analyze product weight and price per gram.

## Tools Used
- SQL
- PostgreSQL
- Kaggle (for the dataset)

## Work Done in SQL

### 1. Data Exploration
I started by exploring the dataset to understand the available information. I checked the total number of records, viewed sample data, searched for missing values, identified product categories, and compared in-stock and out-of-stock products.

I also checked which product names appeared multiple times in the dataset.

### 2. Data Cleaning
In this step, I checked for products with zero MRP or selling price. I removed records with zero MRP and converted the price values from paise to rupees, assuming the original dataset stored prices in paise.

### 3. Business Questions
I used SQL to answer the following questions:

1. What are the top 10 products with the highest discount percentages?
2. Which products have a high MRP but are out of stock?
3. What is the estimated inventory value for each category?
4. Which products have an MRP greater than ₹500 and a discount below 10%?
5. Which five categories have the highest average discounts?
6. Which products offer the best price per gram for products weighing at least 100 grams?
7. How can products be grouped into Low, Medium, and Bulk categories based on weight?
8. What is the total inventory weight for each category?

## SQL Skills Practiced
While working on this project, I practiced the following SQL concepts:

- SELECT and DISTINCT
- WHERE and ORDER BY
- GROUP BY and HAVING
- Aggregate functions such as COUNT, SUM, and AVG
- CASE statements
- Data cleaning and updating records
- Filtering and analyzing product data

## Dataset
The dataset used in this project was downloaded from Kaggle.

**Dataset link:** [Add the original Kaggle dataset URL here]

## How to Run the Project
1. Download the dataset from the original Kaggle source.
2. Create the `zepto` table using the provided SQL script.
3. Import the dataset into PostgreSQL.
4. Run the SQL queries to explore, clean, and analyze the data in the intended order.

## What I Learned
This project helped me improve my SQL skills and understand how SQL can be used to explore data and answer business-related questions. I also learned the importance of checking data quality before performing analysis.

## Note
The inventory value calculated in this project is an estimate based on discounted selling price and available quantity. It does not represent actual sales revenue.
