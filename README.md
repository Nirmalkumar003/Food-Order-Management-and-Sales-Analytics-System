 # 🍔 Food Order Management and Sales Analytics System

A complete **MySQL Database Management System** for managing food ordering, restaurant operations, deliveries, payments, and customer reviews.

This project demonstrates **database design, SQL programming, and sales analytics** using MySQL.

---

## 📌 Project Overview

The Food Order Management and Sales Analytics System is designed to manage the complete food ordering process.

### It includes:

- Customer Management
- Restaurant Management
- Food Categories
- Menu Management
- Order Processing
- Order Items
- Payment Management
- Delivery Partner Management
- Delivery Tracking
- Customer Reviews

---

## 🚀 Features

- ✅ Manage Customers
- ✅ Manage Restaurants
- ✅ Manage Menu Items
- ✅ Place Orders
- ✅ Track Deliveries
- ✅ Record Payments
- ✅ Customer Reviews
- ✅ Sales Analytics

---

## 🗄 Database Tables

| Table | Records |
|-------|--------:|
| Customers | 100 |
| Restaurants | 20 |
| Categories | 10 |
| Menu | 200 |
| Orders | 100 |
| Order_Items | 200 |
| Payments | 100 |
| Delivery_Partners | 30 |
| Deliveries | 100 |
| Reviews | 200 |

---

## 🧱 Database Schema

The project consists of **10 relational tables** connected using **Primary Keys** and **Foreign Keys**.

### Relationships

- Customer → Orders
- Restaurant → Menu
- Category → Menu
- Orders → Order_Items
- Orders → Payments
- Orders → Deliveries
- Delivery_Partners → Deliveries
- Customer → Reviews
- Restaurant → Reviews

---

## 📂 Project Structure

```text
Food-Order-Management-and-Sales-Analytics-System
│
├── SQL
│   ├── 01_Create_Database.sql
│   ├── 02_Create_Tables.sql
│   ├── 03_Insert_Customers.sql
│   ├── 04_Insert_Restaurants.sql
│   ├── 05_Insert_Categories.sql
│   ├── 06_Insert_Menu.sql
│   ├── 07_Insert_Orders.sql
│   ├── 08_Insert_Order_Items.sql
│   ├── 09_Insert_Payments.sql
│   ├── 10_Insert_Delivery_Partners.sql
│   ├── 11_Insert_Deliveries.sql
│   ├── 12_Insert_Reviews.sql
│
├── ERDiagram
│   └── ER_Diagram.png
│
├── README.md
└── LICENSE
```

---

## 💻 Technologies Used

- MySQL 8
- MySQL Workbench
- SQL
- Git
- GitHub

---

## 🔑 Database Concepts Used

- Primary Keys
- Foreign Keys
- Constraints
- AUTO_INCREMENT
- ENUM
- JOIN Operations
- Aggregate Functions
- GROUP BY
- ORDER BY
- Subqueries

---

## 📊 ER Diagram

The ER Diagram is available in the **ERDiagram** folder.

---

## ▶️ How to Run

1. Open MySQL Workbench.
2. Run `01_Create_Database.sql`.
3. Run `02_Create_Tables.sql`.
4. Execute all insert scripts in sequence.
5. Run SQL queries to test the database.

---

## 👨‍💻 Author

**Nirmal Kumar T**

GitHub: **https://github.com/Nirmalkumar003**

---

## ⭐ Future Improvements

- Stored Procedures
- Functions
- Triggers
- Views
- Dashboard Integration
- Java Spring Boot Backend
- Frontend Web Application

---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.
