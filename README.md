# E-commerce Sales Analysis Using SQL

## Project Overview
This project analyzes e-commerce sales data using MySQL to understand revenue performance, product sales, customer spending, and monthly sales trends.

The goal of this project is to use SQL queries to extract meaningful business insights from customer, product, order, and order-item data.

## Tools Used
- **Database:** MySQL
- **Language:** SQL
- **SQL Editor:** OneCompiler
- **Version Control:** GitHub

## Database Structure
The project uses four tables:

- **customers:** Stores customer names and cities.
- **products:** Stores product names, categories, and prices.
- **orders:** Stores customer orders and order dates.
- **order_items:** Stores products and quantities associated with each order.

## Business Questions Answered
1. What is the total sales revenue?
2. How much revenue does each product generate?
3. Which customers generate the highest revenue?
4. Which customers have never placed an order?
5. What is the monthly revenue?
6. What percentage of total revenue comes from each month?
7. How many units of each product were sold?
8. Which product category generates the most revenue?
9. What is the average order value?
10. How does revenue change from one month to the next?
11. Are any customer names or cities missing?
12. Are there any missing or invalid order quantities?

## Key Findings
- **Total Revenue:** ₹81,000
- **Top Revenue-Generating Product:** Laptop — ₹50,000
- **Highest-Spending Customer:** Rahul — ₹60,000
- **Customer Without Orders:** Sneha
- **January 2026 Revenue:** ₹59,000
- **February 2026 Revenue:** ₹22,000
- **Electronics Category Revenue:** ₹60,000
- **Furniture Category Revenue:** ₹21,000
- **Average Order Value:** ₹20,250
- **Month-over-Month Revenue Change:** Revenue decreased by ₹37,000 from January to February 2026, a decrease of approximately 62.71%.

## SQL Concepts Practiced
- CREATE TABLE and INSERT INTO
- Primary keys and foreign keys
- SELECT and WHERE
- Aggregate functions such as SUM and AVG
- INNER JOIN and LEFT JOIN
- GROUP BY and ORDER BY
- Subqueries
- Date formatting using DATE_FORMAT()
- Common Table Expressions (CTEs)
- Window functions using LAG()
- Data-quality checks using IS NULL and conditional filters

## How to Run the Project
1. Open a MySQL-compatible SQL editor.
2. Create the four database tables.
3. Insert the sample customer, product, order, and order-item data.
4. Execute the SQL analysis queries.
5. Review the results to understand sales performance and customer behavior.

**Note:** The project uses MySQL syntax. CTEs and window functions require a compatible MySQL version.

## Project Limitations
- The project uses a small sample dataset for learning and demonstration.
- The findings represent only the sample data and do not reflect the performance of a real business.
- The analysis can be extended by adding more data, products, customers, and business metrics.

## Learning Outcomes
Through this project, I practiced using SQL to analyze sales data, identify top-performing products, understand customer spending patterns, compare monthly revenue, and perform basic data-quality checks.

## Author
Created as a practice project to develop SQL and data-analysis skills for a Data Analyst career.
