# Database Schema Diagram

## Overview
The diagram outlines the database schema for the Baptiste Farm ecommerce platform. It includes tables for users, products, orders, order items, and payments, and shows the relationships between these tables.

## Tables and Columns

### Users
- `id`: Primary key
- `name`
- `email`
- `password_hash`
- `created_at`
- `updated_at`

### Products
- `id`: Primary key
- `name`
- `category`
- `description`
- `price`
- `stock`
- `created_at`
- `updated_at`

### Orders
- `id`: Primary key
- `user_id`: Foreign key
- `total_amount`
- `status`
- `created_at`
- `updated_at`

### Order_Items
- `id`: Primary key
- `order_id`: Foreign key
- `product_id`: Foreign key
- `quantity`
- `price`
- `created_at`
- `updated_at`

### Payments
- `id`: Primary key
- `order_id`: Foreign key
- `payment_method`
- `amount`
- `status`
- `transaction_id`
- `created_at`
- `updated_at`

## Diagram
![Database Schema Diagram](sandbox:/mnt/data/A_clear_and_detailed_database_schema_diagram_for_a.png)
