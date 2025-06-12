# 📊 Demo Database for Business Analytics

This repository contains a structured SQL demo built using a Jupyter Notebook. It simulates a retail business and includes practical SQL queries for solving real-world business problems in customer management, payments, orders, and shipping.

---

## 📁 Contents

- `Demo Database.ipynb` — Jupyter notebook that:
  - ERD 
  - Creates and populates a sample database
  - Runs SQL queries to generate business insights
  - Demonstrates joins, aggregations, and date-based analysis

---

## 🗂️ Database Schema

The demo includes four key tables:

- **Customer**: `customer_id`, `first_name`, `last_name`, `address`, `email`, `tel_number`
- **Orders**: `order_id`, `order_date`, `total_price`, `customer_id`
- **Payment**: `payment_id`, `payment_date`, `amount`, `customer_id`, `order_id`
- **Shipment**: `shipment_id`, `order_id`, `shipment_date`, `delivery_date`, `status`

---

## 🔍 Sample Business Queries

- Top 5 customers by total spend
- Monthly revenue trends
- Orders with no payments
- Average order value per customer
- Average delivery time over the last 6 months

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/demo-database.git
   cd demo-database
