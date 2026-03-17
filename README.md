# 🍕 Pizza Sales SQL Project

## 📌 Project Overview
This project analyzes pizza sales data using SQL to extract meaningful insights.

## 📊 Key Analysis
- Top 5 most ordered pizzas
- Total revenue generated
- Peak order times
- Category-wise sales

## 🛠️ Tools Used
- SQL (PostgreSQL)
- Excel (for dataset)

## 📈 Sample Queries
```sql
SELECT pizza_name, COUNT(*) AS total_orders
FROM orders
GROUP BY pizza_name
ORDER BY total_orders DESC
LIMIT 5;
