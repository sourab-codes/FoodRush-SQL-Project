# 🍔 FoodRush SQL Project

A complete **food delivery database project** built using **MySQL**. The project demonstrates relational database design, SQL querying, advanced SQL features, and business-oriented data analysis.

## 📌 Project Overview

**FoodRush** is a food delivery platform database designed to manage customers, restaurants, menus, orders, payments, deliveries, delivery partners, coupons, and customer reviews.

The project focuses on building a structured relational database and using SQL to answer real-world business questions.

## 🎯 Objectives

* Design a normalized relational database for a food delivery platform
* Create relationships between multiple business entities
* Perform data retrieval and manipulation using SQL
* Analyze customer, restaurant, order, payment, and delivery data
* Use advanced SQL techniques for business analysis
* Implement database objects such as views, procedures, functions, triggers, and events

## 🗄️ Database Structure

The database contains **11 relational tables**:

| Table               | Purpose                             |
| ------------------- | ----------------------------------- |
| `customers`         | Stores customer information         |
| `restaurants`       | Stores restaurant information       |
| `food_categories`   | Stores food categories              |
| `menu_items`        | Stores restaurant menu items        |
| `delivery_partners` | Stores delivery partner information |
| `coupons`           | Stores discount coupon information  |
| `orders`            | Stores customer orders              |
| `order_items`       | Stores items included in each order |
| `payments`          | Stores payment information          |
| `deliveries`        | Stores delivery information         |
| `reviews`           | Stores customer reviews and ratings |

## 🔗 Database Relationships

The database uses primary keys and foreign keys to maintain relationships between tables.

Key relationships include:

* Customers → Orders
* Restaurants → Menu Items
* Food Categories → Menu Items
* Orders → Order Items
* Orders → Payments
* Orders → Deliveries
* Delivery Partners → Deliveries
* Customers → Reviews
* Restaurants → Reviews
* Coupons → Orders

## 🧠 SQL Concepts Used

### SQL Fundamentals

* `SELECT`
* `WHERE`
* `DISTINCT`
* `ORDER BY`
* `LIMIT`
* `LIKE`
* `BETWEEN`
* `IN`
* `IS NULL`
* `IS NOT NULL`
* Comparison operators
* Logical operators

### Aggregation

* `COUNT()`
* `SUM()`
* `AVG()`
* `MIN()`
* `MAX()`
* `GROUP BY`
* `HAVING`

### Joins

* `INNER JOIN`
* `LEFT JOIN`
* `RIGHT JOIN`
* Multi-table joins
* Self joins

### Advanced SQL

* Subqueries
* Correlated subqueries
* `EXISTS`
* `NOT EXISTS`
* `ANY`
* `ALL`
* CTEs
* `CASE`
* Window functions

### Window Functions

The project includes:

* `ROW_NUMBER()`
* `RANK()`
* `DENSE_RANK()`
* `LAG()`
* `LEAD()`

These are used for ranking, comparisons, and analyzing records across related rows.

## ⚙️ Database Objects

The project also demonstrates several MySQL database objects.

### Views

* `customer_order_details`
* `restaurant_performance`
* `delivery_partner_performance`

### Stored Procedures

* `placeorder`
* `customerspendingreport`

### Functions

* `calculatedeliverycharge`
* `customercategory`

### Triggers

* `update_order_total`
* `update_order_status_after_payment`
* `validate_review_rating`

### Event

* `update_coupon_status`

## 📊 Business Analysis

The project uses SQL to analyze real-world food delivery business questions such as:

* Customer spending behavior
* Restaurant performance
* Average order value
* Restaurant sales
* Delivery performance
* Customer ratings
* Popular menu items
* Category-wise sales
* Order trends
* Customer segmentation
* Delivery charges
* Payment analysis

## 📈 Project Dataset

The database contains sample data across all major business entities, including:

* **50** customers
* **15** restaurants
* **10** food categories
* **105** menu items
* **25** delivery partners
* **20** coupons
* **350** orders
* **698** order items
* **350** payments
* **285** deliveries
* **159** reviews

## 🛠️ Technologies Used

* **MySQL**
* **MySQL Workbench**
* **SQL**
* **Database Design**
* **ER Diagram**

## 🚀 How to Run

### 1. Install MySQL

Install MySQL and MySQL Workbench.

### 2. Open the SQL file

Open:

```text
foodrush.sql
```

in MySQL Workbench.

### 3. Execute the script

Run the SQL script to create the database, tables, relationships, sample data, queries, and database objects.

### 4. Explore the database

After execution, you can explore the tables and run the analytical queries included in the project.

## 📁 Project Files

```text
FoodRush-SQL-Project/
│
├── foodrush.sql
├── ER.Digram.mwb
└── README.md
```

## 📌 Key Skills Demonstrated

This project demonstrates practical experience with:

**SQL • MySQL • Relational Database Design • Data Analysis • Joins • Subqueries • CTEs • Window Functions • Views • Stored Procedures • Functions • Triggers • Events**

## 👨‍💻 Author

**Sourab Galphade**

GitHub: [@sourab](https://github.com/sourab)

---

⭐ If you find this project useful, feel free to explore the repository.
