<img width="1912" height="1017" alt="image" src="https://github.com/user-attachments/assets/e305d8ef-aed4-4085-8a24-d2394b1f70fd" /># shopstore-db-sql
A complete SQL project for managing products, customers, and orders in a shopping store
**Shopping Store SQL Project**
**🎯 Objective**
The objective of this project is to design and implement a relational database for a shopping store that demonstrates one-to-many and many-to-many relationships using four tables:
customers
orders
products (with price column)
order_items

**Questions / KPIs**
How many orders has each customer placed?
What are the details of products purchased in each order?
What is the total sales amount per order and per customer?
Which products generate the most revenue?
What is the overall store revenue?

**⚙️ Process**
Database Schema Design
Defined tables: customers, orders, products, and order_items.
Established relationships:
One-to-Many → customers → orders.
Many-to-Many → orders ↔ products through order_items.
SQL Implementation
Created tables with primary and foreign keys.
Inserted sample data.
Wrote SQL queries to answer the business questions.
Data Analysis
Aggregated order and product-level data.
Calculated sales revenue per customer and per product.

**📸 Dashboard Preview**
<img width="1912" height="1017" alt="SQLScreenshot 2025-09-10 160228" src="https://github.com/user-attachments/assets/2beb6117-87e0-488d-a861-965da2e72676" />


**✅ Final Conclusion**
This project demonstrates how relational database design can effectively represent real-world business scenarios like a shopping store. By establishing one-to-many and many-to-many relationships, we can analyze customer behavior, order patterns, and product performance.

