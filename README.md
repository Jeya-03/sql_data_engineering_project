# SQL_project_data_enginnering
This is a practical learning project based on my self-study of SQL in MySQL as a part of my data engineering basics preparation. The SQL commands for this is in __sql_commands__ file
It demonstrates how to design and query a relational database for a restaurant’s online ordering and booking system, similar to Zomato. The work includes schema creation, sample data insertion, and analytical SQL queries for business insights.

Features:

1.Database Design:

i) categories – food types (Veg, Non-Veg, Vegan)

ii) items – menu items with prices and category IDs

iii) order_items – order details referencing items

iv) orders – customer orders with delivery details

v) payments – payment info (method, status, amount, date)

vi) users – customer details (name, contact, email)

2. ETL / SQL Analysis:

i)Total revenue from all orders

ii) Revenue by item

iii) Revenue by payment method

iv) Total revenue by date

v) Total orders and revenue by user

vi) Items ordered by category

vii) Orders by payment status

viii) Users with most orders

ix) Revenue by category

x) Items purchased in a specific order

xi) Customer details with orders

xii) Revenue by customer

Insights Provided:

*) Overall and per-item revenue

*) Popular items and categories

*) Payment method performance

*) Top spending customers

*) Daily revenue trends

How to Use

-> Create a database named zomato and run the provided table-creation scripts.

-> Insert the sample data for categories, items, users, orders, order_items and payments.

-> Execute the SQL queries to generate the analytics listed in the code file.
