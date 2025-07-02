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

## 📂 Folder Structure

```
├── README.md
├── schema/
│   ├── create_tables.sql
│   └── insert_dummy_data.sql
├── queries/
│   └── business_queries.sql
├── docs/
│   ├── EERD.pdf
│   └── data_dictionary.pdf
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

## 📚 References

1. Beaulieu, A. (2009). *Learning SQL*. O'Reilly.
2. Obe, R. O., & Hsu, L. S. (2017). *PostgreSQL: Up and Running*. O'Reilly.
3. Russo, J. (2017). *SQL by Example*. Momentum Press.
4. Wilton, P., & Colby, J. (2005). *Beginning SQL*. Wiley.
5. Ghlala, R. (2019). *Analytic SQL in SQL Server*. Wiley.
6. [W3Schools SQL Tutorial](https://www.w3schools.com/sql/)

## 🤝 Collaboration

This project was a team effort, carried out with regular virtual meetings and shared responsibilities across design, development, and testing.

## 📌 License

This repository is for academic purposes only.
