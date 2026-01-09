# 📦 Stationery Store Management System (Java)

A **Java-based desktop application** for managing a stationery store, built using the **DAO (Data Access Object) pattern**.  
This project focuses on applying core Java concepts, database interaction, and real-world business logic.

---

## 🚀 Project Overview

The Stationery Store Management System is designed to support daily store operations such as:
- User authentication
- Product and category management
- Order and invoice handling
- Revenue statistics
- Excel export for reports

The project is suitable for learning and demonstrating skills in **Java**, **OOP**, **DAO architecture**, and **database-driven applications**.

---

## 🧩 Main Features

### 👤 Account & Authentication
- Login / Register functionality
- Account management
- Role-based access (Admin / Staff)

### 👥 Customer & Staff Management
- Manage customer information
- Manage staff (human resources)
- Supplier management

### 📦 Product Management
- Add, update, delete products
- Manage product categories
- Supplier-product relationships

### 🧾 Order & Invoice
- Create and manage orders
- Generate invoices
- Order and invoice status tracking

### 📊 Revenue & Reports
- Revenue statistics
- Sales reports
- Export data to **Excel**

---

## 🏗️ System Architecture

The application follows a layered architecture using the **DAO pattern**:

UI Forms -> Service / Business Logic -> DAO Layer -> Database
- Clear separation of concerns
- Easy maintenance and extension
- Reusable data access layer

---

## 📂 DAO Components

The project includes the following DAO classes:

- `AccountDAO`
- `LoginDAO`
- `RegisterDAO`
- `CustomerDAO`
- `NhanSuDAO`
- `NhaCungCap_DAO`
- `Category_DAO`
- `ProductDAO`
- `DonHang_DAO`
- `HoaDon_DAO`
- `DoanhThu_DAO`

Each DAO is responsible for handling **CRUD operations** and database interactions for its corresponding entity.

---

## 🖥️ User Interface

- Java Swing / JavaFX Forms
- Separate forms for each functional module
- User-friendly and easy-to-navigate layout

---

## 🛠️ Technologies Used

- **Java**
- **JDBC**
- **DAO Design Pattern**
- **MySQL / SQL Server**
- **Apache POI** (Excel export)
- **Java Swing / JavaFX**

---

## ⚙️ Installation & Setup

```bash
1. Clone the repository:
git clone https://github.com/DuyHoan23/Stationery-store-manager-Java.git
2. Import the project into:

IntelliJ IDEA / Eclipse / NetBeans

3. Configure database connection:

Update database credentials in the configuration file

4. Run the main application class

```

## Author

Hoan Duy | Information Technology Engineer

GitHub: https://github.com/DuyHoan23
## License

MIT License

Email: hoan3798@gmail.com
