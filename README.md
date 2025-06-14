## 🛒 E-Commerce Database Project (SQL)
📌 Overview
This project presents a comprehensive relational database design for an E-Commerce platform, created using SQL. It simulates the real-world operations of an online retail system, covering everything from customers and products to orders, payments, inventory, and delivery. The schema has been carefully normalized and includes over 25 interrelated tables to support business logic and analytics needs.

## 🧩 Features
Complete support for Product Catalog, including categories, brands, colors, and sizes.

Customer management with support for delivery addresses and shopping carts.

Inventory tracking through stocks, stores, and store products.

Fully implemented Order & Payment system, including statuses and methods.

Employee and store management for multi-store operations.

Rich use of foreign keys, constraints, and normalization to ensure data integrity.

## 🗂️ Database Tables
Key tables in the database include:

products, product_detail, brands, product_categories

customers, delivery_addresses, shopping_cart, cart_items

orders, order_detail, payments, payment_methods

stocks, product_stock, store_products, stores

employees, store_employees, personal_types

cities, colors, measur_types, measur

Each table includes metadata columns: insert_date, update_date, and row_status for data tracking and logical deletion.

## 📊 ER Diagram
The Diagrams.pdf file in the repository provides a full Entity-Relationship Diagram that visually represents the database structure and relationships.

## ⚙️ Technologies Used
SQL Server (T-SQL)

SSMS (SQL Server Management Studio)

Relational Database Design principles

Normalization & Referential Integrity

## 🧪 How to Use
Clone the repository.

Use the .sql files provided in the project (inside e_commerse.zip) to create the database.

Open and execute in SQL Server Management Studio.

Explore and query using the relational structure.

## 🎯 Use Cases
Ideal for learning database normalization and relationship design.

Useful as a backend for e-commerce projects or for mock business intelligence applications.

Can be extended with procedures, triggers, and views.

## 📁 Files Included
Diagrams.pdf – Entity-Relationship Diagram

SQL scripts (in e_commerse.zip) – for table creation and data structure

Future enhancements can include sample data, procedures, and views.
