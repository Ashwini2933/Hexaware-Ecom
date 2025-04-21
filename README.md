# Hexaware-Ecom
Ecom application case study
# 🛒 Ecommerce Application

This is a console-based Java Ecommerce Application developed as part of an End Of Module (EOM) project. The application allows customers to browse products, place orders, and manage inventory. It simulates an end-to-end ecommerce system with core functionalities like product management, order processing, and customer handling.

## 🚀 Features

- Customer Registration and Login
- Product Catalog (View All, Filter by Category)
- Shopping Cart Functionality
- Place and View Orders
- Inventory Management
- Admin Panel for Product and Inventory Control
- Exception Handling and Input Validation
- Database Integration using JDBC

## 🛠️ Tech Stack

- **Java** (OOP Principles)
- **MySQL** for Database
- **JDBC** for Database Connectivity
- **Collections Framework**
- **JUnit** for Testing (optional)
- **Maven** (optional, for dependency management)

## 📂 Project Structure

## 🧪 Sample Classes

- `Customer.java`
- `Product.java`
- `Order.java`
- `OrderDetail.java`
- `Inventory.java`
- `CustomerDAO`, `ProductDAO`, etc.

## 🔌 Database Setup

1. Create a MySQL database named `ecommerce_db`.
2. Run the provided SQL script `schema.sql` to create tables.
3. Update `DBUtil.java` with your MySQL username and password.

## 🏁 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ecommerce-app.git
   cd ecommerce-app
javac com/ecommerce/app/EcommerceApp.java
java com.ecommerce.app.EcommerceApp

