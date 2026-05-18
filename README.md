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

* Exploratory analysis of books, customers, and orders 
  including total stock, revenue, and genre distribution

* Customer segmentation by order frequency to identify 
  repeat buyers and high-value spenders

* Genre-wise sales analysis by quantity sold and total 
  revenue to rank top performing categories

* Seasonal demand analysis — monthly order trends by genre 
  to uncover purchase spikes and demand patterns

* Mystery genre deep-dive — monthly orders, revenue, and 
  AOV to identify distinct high-volume vs high-value windows

* Author-wise quantity analysis to identify top contributors 
  to total book sales

* Geographic analysis — cities where high-spending customers 
  are located (orders exceeding $30)

* Inventory analysis — total stock availability and 
  low-stock book identification

* Price analysis — most and least expensive books, 
  average price by genre (Fantasy)

* Popularity analysis — most frequently ordered book 
  identification
  
  ---

## Key Insights

- 139 out of 307 customers (45.28%) are repeat buyers — nearly 1 in 2 customers returned, indicating strong 
  retention potential and loyalty base worth targeting with personalized campaigns.
- Mystery genre peaked in November (14 orders, 2x monthly average) but January generated highest revenue (₹2,121) 
  with 19% higher AOV (₹176 vs ₹148) — indicating two distinct demand windows needing different strategies


---

## 🧾 SQL Concepts Used

* SELECT, WHERE
* GROUP BY, ORDER BY
* JOIN (INNER JOIN)
* Aggregate Functions (SUM, COUNT, AVG)
* Subqueries
* LIMIT
* DATE Functions (MONTH, BETWEEN)

---


## 📈 Future Improvements

* Power BI dashboard
* Perform advanced analytics (RFM, churn analysis)

---

## Author
Apurwa Sahu
