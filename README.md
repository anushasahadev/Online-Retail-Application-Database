🛒 Online Retail Application Database
📌 Overview
This SQL project models the core backend of an online retail platform. It simulates how customers, employees, and products interact within a transactional ecosystem. The schema is designed to demonstrate real-world business logic for e-commerce operations, covering user management, order processing, product inventory, payment tracking, and delivery workflows.

🧱 Database Schema
The project contains 10 interrelated tables organized within the online_retail_app schema:

user_login: Admin or system users with login credentials.

customers: End users who purchase products from the platform.

employees: Staff responsible for delivery and backend support.

employment_type: Distinguishes internal employees and vendors.

product_items: Product catalog with stock, price, discount, and image info.

orders: Customer purchase records linked to payments and delivery.

order_items: Junction table between orders and purchased items.

order_delivery: Tracks delivery status in stages.

payment: Payment transaction data including mode, amount, and status.

🎯 Learning Objectives
Apply SQL DDL to design and manage relational schemas.

Practice data normalization, foreign keys, and integrity constraints.

Simulate real-world business process mapping in an e-commerce setting.

Understand key relationships like one-to-many (e.g., customer-orders), many-to-many (orders-products via order_items), and one-to-one (order-payment).

💻 Use Cases & Scenarios
You can build queries around:

Top-selling products by revenue or volume

Customers with the highest spend

Delivery performance by employee

Unsuccessful payment transactions

Inventory analysis: low-stock or overstock items

🔧 Technologies
PostgreSQL
