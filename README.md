# Zepto SQL Data Analysis Project

## Project Overview
This project explores Zepto product data using SQL to analyze product pricing, discounts, stock availability, and inventory across categories. The dataset was sourced from Kaggle.

## Objectives
- Explore the product dataset and understand its structure.
- Identify missing values, zero-priced products, and repeated product names.
- Analyze product discounts and pricing patterns.
- Compare in-stock and out-of-stock products.
- Estimate inventory value and analyze product weights across categories.

## Tools and Technologies
- SQL
- PostgreSQL
- Kaggle dataset

## SQL Analysis Performed

### 1. Data Exploration
- Counted records and inspected sample data.
- Checked for missing values.
- Identified product categories.
- Compared stock availability.
- Found product names associated with multiple SKUs.

### 2. Data Cleaning
- Identified products with zero MRP or selling price.
- Removed records with zero MRP.
- Converted price values from paise to rupees, assuming the original dataset uses paise.

### 3. Business Questions
1. What are the top 10 products by discount percentage?
2. Which high-MRP products are out of stock?
3. What is the estimated inventory value by category?
4. Which products have an MRP above ₹500 and a discount below 10%?
5. Which five categories have the highest average discount?
6. Which products offer the lowest price per gram?
7. How can products be grouped by weight into Low, Medium, and Bulk categories?
8. What is the total inventory weight by category?

## Skills Demonstrated
SQL querying, filtering, aggregation, sorting, data cleaning, `GROUP BY`, `HAVING`, `CASE` statements, `DISTINCT`, and aggregate functions.

## Dataset
The dataset was sourced from Kaggle. Add the original dataset URL here: [Insert Kaggle dataset link]

## How to Run
1. Download the dataset from the original Kaggle source.
2. Create the `zepto` table using the SQL script.
3. Import the data into PostgreSQL.
4. Execute the exploration, cleaning, and analysis queries in the intended order.

## Disclaimer
The inventory value calculated in this project is an estimate based on discounted selling price and available quantity. It should not be interpreted as actual sales revenue.
