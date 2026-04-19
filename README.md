# online-bookstore-analysis (SQL Project)

## Objective

This project analyzes an online bookstore dataset to understand customer behavior, sales trends, and revenue patterns.
The goal is to extract meaningful business insights using SQL.

---

## Tools & Technologies

* MySQL
* SQL
* Excel (for data preview)

---

## Dataset Description

The dataset consists of three tables:

* **Customers** → Contains customer details (ID, name, city, country)
* **Books** → Contains book information (title, author, price)
* **Orders** → Contains transaction data (customer purchases, quantity, date)

---

## Database Structure

The project uses relational tables connected through keys:

* Customers → Customer_ID
* Books → Book_ID
* Orders → Customer_ID, Book_ID

---

## Key Analysis Performed

* Total number of customers, books, and orders
* Total revenue generated from orders
* Top-selling books based on quantity sold
* Most valuable customers by total spending
* Repeat vs new customer distribution
* Monthly order trends and seasonality
* Genre-wise sales performance
* Author-wise total books sold
* High-value orders and spending patterns
* Inventory analysis (total stock & low-stock books)
* Most expensive and cheapest books
* Frequently ordered books (popularity analysis)
* Geographic distribution of customers
* High-revenue cities or regions
* Average book price by genre

---

## Key Insights

- Repeat customers contribute a major share of total revenue, highlighting strong customer retention.
- A small group of books drives the majority of sales, indicating demand concentration on popular titles.
- Customer retention plays a key role in business growth

---

## 🧾 SQL Concepts Used

* SELECT, WHERE
* GROUP BY, ORDER BY
* JOIN (INNER JOIN)
* Aggregate Functions (SUM, COUNT, AVG)
* Subqueries

---


## 📈 Future Improvements

* Power BI dashboard
* Perform advanced analytics (RFM, churn analysis)

---

## Author
Apurwa Sahu
