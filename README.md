🔍 Objective
The goal of this task is to use SQL to extract and analyze product stock data from the provided Sale Report.csv dataset.

📁 Dataset
Filename: Sale Report.csv
Description: The dataset contains details about product variants including SKU code, design number, available stock, category, size, and color.

💻 Tools Used
SQLite (You can also use MySQL/PostgreSQL)

DB Browser for SQLite (optional GUI)

🧠 SQL Features Demonstrated
Basic SELECT, WHERE, ORDER BY

Aggregation with SUM, AVG

Grouping using GROUP BY

Filtering with HAVING

Creating views

Subqueries

Indexing for query optimization

📊 Sample SQL Analyses
Total products and stock

Stock by category, size, and color

Most stocked designs

Designs with stock above average

Products with low stock alerts

🧪 Deliverables
queries.sql: Contains all the SQL queries

Sale Report.csv: Original dataset

screenshots/: Screenshots of query outputs

This README.md file

❓ Interview Questions Answered
Difference between WHERE and HAVING
WHERE filters rows before aggregation, HAVING filters after.

Types of JOINs
INNER, LEFT, RIGHT, FULL OUTER (not used here, but explained if asked).

Average Revenue per User
(N/A here, but would be: SUM(revenue)/COUNT(DISTINCT user_id))

Subqueries
A query inside another query (used to compare stock to average).

Optimizing SQL Queries
Using indexes, limiting columns, and avoiding unnecessary subqueries.

Views
Saved SQL queries acting as virtual tables for simplified access.

Handling NULLs
Use IS NULL, COALESCE(), or filtering as needed (not applicable here).

