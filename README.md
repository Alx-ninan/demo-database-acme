# 📊 Demo Database for Business Analytics

This repository contains a structured SQL demo built using a Jupyter Notebook. It simulates a retail business and includes practical SQL queries for solving real-world business problems in customer management, payments, orders, and shipping.

---

## 📁 Contents

[Demo Database-View All Queries](https://github.com/Alx-ninan/demo-database-acme/blob/main/Demo%20Database.ipynb):
  
  - Creates and populates a sample database
  - Runs SQL queries to generate business insights
  - Demonstrates joins, aggregations, and date-based analysis

---

## 🗂️ Database Schema

The demo includes four key tables:

- **Customer**: `customer_id`, `first_name`, `last_name`, `address`, `email`, `tel_number`
- **Orders**: `order_id`, `order_date`, `total_price`, `customer_id`
- **Payment**: `payment_id`, `payment_date`, `amount`, `customer_id`, `order_id`
- **Shipment**: `shipment_id`, `order_id`, `shipment_date`

---

## 🔍 Sample Business Queries

- Top 5 customers by total spend
- Monthly revenue trends
- Average order value per customer


---

## ERD
![Image](https://github.com/Alx-ninan/demo-database-acme/blob/main/ACME%20CO%20-%20ERD.png)
