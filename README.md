# 🍕 Pizza Sales SQL Analysis

## 📌 Project Overview

This project analyzes pizza sales data using **SQL** to understand order patterns, revenue, customer preferences, and pizza performance.

The analysis uses multiple SQL queries involving **aggregation, grouping, filtering, sorting, joins, date/time functions, and subqueries** to answer important business questions about pizza sales.

## 🎯 Project Objectives

The main objective of this project is to analyze pizza sales data and extract meaningful business insights, including:

- Total number of orders
- Total revenue generated
- Highest-priced pizza
- Most commonly ordered pizza size
- Top 5 most ordered pizza types
- Pizza category performance
- Hourly order distribution
- Daily order trends
- Average pizzas ordered per day
- Revenue contribution by pizza type

## 🗂️ Dataset

The project uses pizza sales data containing information about:

- Orders
- Order dates and times
- Pizza types
- Pizza categories
- Pizza sizes
- Pizza prices
- Quantity ordered

### Main Tables

The analysis uses the following tables:

- `orders`
- `order_details`
- `pizzas`
- `pizza_types`

These tables are joined where necessary to obtain complete information about orders, pizzas, categories, prices, and quantities.

## 🔍 SQL Analysis & Business Questions

### 1. Total Number of Orders

Retrieve the total number of orders placed.

**SQL Concepts:** `COUNT()`

---

### 2. Total Revenue

Calculate the total revenue generated from pizza sales.

**SQL Concepts:** `SUM()`, multiplication

---

### 3. Highest-Priced Pizza

Identify the pizza with the highest price.

**SQL Concepts:** `MAX()`, `ORDER BY`, `LIMIT`

---

### 4. Most Common Pizza Size

Identify the most frequently ordered pizza size.

**SQL Concepts:** `GROUP BY`, `COUNT()`, `ORDER BY`, `LIMIT`

---

### 5. Top 5 Most Ordered Pizza Types

List the top 5 most ordered pizza types along with their total quantities.

**SQL Concepts:** `JOIN`, `SUM()`, `GROUP BY`, `ORDER BY`, `LIMIT`

---

### 6. Total Quantity by Pizza Category

Join the necessary tables to determine the total quantity of pizzas ordered for each pizza category.

**SQL Concepts:** `JOIN`, `SUM()`, `GROUP BY`

---

### 7. Distribution of Orders by Hour

Determine how orders are distributed throughout the day based on the hour of the order.

**SQL Concepts:** `HOUR()`, `GROUP BY`, `COUNT()`

---

### 8. Category-Wise Pizza Distribution

Join the relevant tables to analyze the distribution of pizzas across different categories.

**SQL Concepts:** `JOIN`, `GROUP BY`, `COUNT()`

---

### 9. Average Number of Pizzas Ordered Per Day

Group orders by date and calculate the average number of pizzas ordered per day.

**SQL Concepts:** `GROUP BY`, `SUM()`, `AVG()`, date functions

---

### 10. Revenue Contribution by Pizza Type

Calculate the percentage contribution of each pizza type to the total revenue.

**SQL Concepts:** `SUM()`, `GROUP BY`, subqueries, percentage calculations

## 🛠️ SQL Skills Demonstrated

This project demonstrates practical use of:

- `SELECT`
- `WHERE`
- `COUNT()`
- `SUM()`
- `AVG()`
- `MAX()`
- `GROUP BY`
- `ORDER BY`
- `LIMIT`
- `JOIN`
- `INNER JOIN`
- Aggregate Functions
- Date & Time Functions
- Subqueries
- Percentage Calculations
- Data Aggregation

## 📊 Key Analysis Areas

The project focuses on four major areas:

### 📦 Order Analysis
Understanding total orders, order quantities, and order timing.

### 💰 Revenue Analysis
Analyzing total revenue, highest-priced pizzas, and revenue contribution by pizza type.

### 🍕 Product Analysis
Identifying the most popular pizza sizes, pizza types, and categories.

### ⏰ Time-Based Analysis
Understanding when customers place orders and analyzing daily and hourly order patterns.

## 📁 Project Structure

```text
Pizza-Sales-SQL-Project/
│
├── README.md
│
├── pizza_sales.sql
│
└── queries/
    ├── query_01_total_orders.sql
    ├── query_02_total_revenue.sql
    ├── query_03_highest_priced_pizza.sql
    ├── query_04_most_common_size.sql
    ├── query_05_top_5_pizzas.sql
    ├── query_06_quantity_by_category.sql
    ├── query_07_orders_by_hour.sql
    ├── query_08_category_distribution.sql
    ├── query_09_average_pizzas_per_day.sql
    └── query_10_revenue_contribution.sql
```

## 💻 Tools Used

- **MySQL**
- **MySQL Workbench**
- **Git & GitHub**


## 📈 What This Project Demonstrates

This project demonstrates the ability to use SQL for **real-world business data analysis** rather than only writing basic queries.

It covers:

- Extracting business metrics
- Combining data from multiple tables
- Identifying top-performing products
- Analyzing customer ordering patterns
- Measuring revenue performance
- Performing time-based analysis
- Converting raw sales data into useful insights

## 👤 Author

**Mayank Chamola**

GitHub: `https://github.com/mayankchamola`

---

