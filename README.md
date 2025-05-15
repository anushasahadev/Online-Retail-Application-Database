# 🛒 Online Retail Application Database

## 📌 Overview

This SQL project models the core backend of an online retail platform. It simulates how customers, employees, and products interact within a transactional ecosystem. The schema is designed to demonstrate real-world business logic for e-commerce operations, covering user management, order processing, product inventory, payment tracking, and delivery workflows.

---

## 🧱 Database Schema

The project contains 10 interrelated tables organized within the `online_retail_app` schema:

* **user\_login**: Admin or system users with login credentials.
* **customers**: End users who purchase products from the platform.
* **employees**: Staff responsible for delivery and backend support.
* **employment\_type**: Distinguishes internal employees and vendors.
* **product\_items**: Product catalog with stock, price, discount, and image info.
* **orders**: Customer purchase records linked to payments and delivery.
* **order\_items**: Junction table between orders and purchased items.
* **order\_delivery**: Tracks delivery status in stages.
* **payment**: Payment transaction data including mode, amount, and status.

---

## 🎯 Learning Objectives

* Applied **SQL DDL** to design and manage relational schemas.
* Practiced **data normalization**, foreign keys, and integrity constraints.
* Simulated real-world **business process mapping** in an e-commerce setting.
* Understanding key relationships like one-to-many (e.g., customer-orders), many-to-many (orders-products via order\_items), and one-to-one (order-payment).

---

## 💻 Use Cases & Scenarios

* Top-selling products by revenue or volume
* Customers with the highest spend
* Delivery performance by employee
* Unsuccessful payment transactions
* Inventory analysis: low-stock or overstock items

---

## 🔧 Technologies

* SQL (PostgreSQL)
* Can be run on platforms like pgAdmin, DBeaver, or any PostgreSQL-compatible environment



