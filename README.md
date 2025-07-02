# FM Clothing Store Database Project

This project is part of a university coursework assignment on **Data Management**. The primary goal was to **design and develop a PostgreSQL relational database** system for FM Clothing Store, a retailer managing multiple branches, products, and sales channels.

## 📘 Project Overview

The system is built to manage:

* Store branches and employees
* Product inventory and categories
* Customer information
* Order processing and delivery
* Product reviews and stock tracking

The solution includes a normalized database structure (3NF), SQL scripts for schema creation and data insertion, and sample queries for business insights.

## 👥 Team Members

* UP2280648
* UP2298397
* UP2299529

## 📊 Entity-Relationship Model

The Enhanced Entity-Relationship Diagram (EERD) maps out relationships between the core entities, including:

* **One-to-many**, **one-to-one**, and **many-to-many** relationships using join tables like `Order_Details` and `Product_Stock`.

## 🧱 Database Schema

The schema includes the following main tables:

* `Branch`
* `Employees`
* `Manager`
* `Category`
* `Product`
* `Customer`
* `Orders`
* `Order_Details`
* `Product_Stock`
* `Delivery`
* `Reviews`

Each table includes properly defined primary and foreign keys, constraints, and domain rules.

```

## 💡 Key Features

* **Branch-based order processing**: Every order is tied to a specific branch, including online orders.
* **Stock tracking**: `Product_Stock` table tracks quantity across five branches.
* **Customer and order management**: Tracks orders, payments, delivery, and reviews.
* **SQL reports**: Pre-built queries generate sales, delivery, product availability, and customer insights.

## 🧪 Example Queries

* Monthly revenue per branch (Sept & Oct 2024)
* Top 3 selling products
* Products with ratings below 4
* Stock levels under threshold
* Orders per delivery method

## 📈 Business Use Cases

* Inventory management
* Sales reporting
* Customer relationship tracking
* Delivery status and performance
* Product quality analysis via reviews

## 🛠️ Technologies Used

* **PostgreSQL**
* **SQL**
* **ERD tools** (e.g., draw\.io, Lucidchart)


## 🤝 Collaboration

This project was a team effort, carried out with regular virtual meetings and shared responsibilities across design, development, and testing.

## 📌 License

This repository is for academic purposes only.
