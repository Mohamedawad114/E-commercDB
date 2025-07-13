🛒 E-Commerce Database Design
📌 Overview
This project presents a simplified relational database schema for an e-commerce system. It includes essential tables to manage users, products, orders, and payments.

🧱 Features
User account management

Product listings with categories

Order placement and detailed tracking

Payment handling

Support for multiple items per order

🗃️ Main Tables
user: Stores user information such as name, email, and address

product: Contains product details like name, price, and quantity

category: Defines product categories

orders: Main order table, one per transaction

order_details: Holds items and quantities related to each order

set_order: Temporary order table used before final checkout (like a cart)

payment: Records payment method and status

💾 Tech Stack
MySQL (compatible with any relational DBMS)

SQL DDL statements for schema creation

🚀 How to Use
Clone the project

Import the SQL schema into your database

Optionally insert sample data for testing

Connect with backend code or use for learning purposes

📎 Note
This schema is suitable for learning or prototyping. It can be extended to include advanced features such as user roles, discount codes, shipping management, and product images.

