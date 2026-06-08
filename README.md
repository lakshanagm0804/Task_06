📊 Task 6: Sales Trend Analysis Using Aggregations
🎯 Objective

The objective of this task is to analyze monthly revenue and order volume using SQL aggregation functions. The analysis helps identify sales trends over time and provides useful business insights.

🛠️ Tools Used
🐬 MySQL
📄 MySQL Workbench
🗂️ Dataset

Table Name: online_sales

Column Name	Description
🆔 order_id	Unique identifier for each order
📅 order_date	Date when the order was placed
💰 amount	Revenue generated from the order
📦 product_id	Unique identifier for the product
📚 SQL Concepts Used
📆 YEAR()
📅 MONTH()
🧮 SUM()
🔢 COUNT(DISTINCT)
📂 GROUP BY
🔀 ORDER BY
🎯 WHERE (Filtering specific time periods)
✅ Task Performed
✔️ Created the online_sales table.
✔️ Inserted 100 sample sales records.
✔️ Extracted the year and month from the order_date.
✔️ Grouped the data by year and month.
✔️ Calculated the monthly revenue using SUM(amount).
✔️ Calculated the monthly order volume using COUNT(DISTINCT order_id).
✔️ Sorted the results using ORDER BY.
✔️ Filtered data for a specific time period using the WHERE clause.

The query generates a monthly sales summary containing:

💰 Total Revenue
🛒 Total Order Volume
📅 Month-wise Sales Analysis
📊 Chronological Sorting of Data

This allows easy identification of sales patterns and business trends.

🎓 Learning Outcome

Through this task, I learned how to:

🔹 Aggregate data using SQL functions.
🔹 Group records based on multiple columns.
🔹 Analyze monthly business performance.
🔹 Sort and filter data efficiently.
🔹 Generate meaningful insights from raw sales data.
📦 Deliverables
📜 SQL Script (Task6_Sales_Trend_Analysis.sql)
📊 Results Table (Exported from MySQL)
📝 README Documentation
