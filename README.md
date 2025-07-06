# Task-7
# 🧑‍💼 Employee Database App (Java + JDBC + MySQL)

This is a simple Java console application that performs **CRUD operations** (Create, Read, Update, Delete) on an **Employee** table using **JDBC** to connect to a **MySQL database**.

---

## 📋 Features

- ✅ Add a new employee
- ✅ View all employees
- ✅ Update employee details
- ✅ Delete an employee by ID
- ✅ MySQL database connection using JDBC

---

## 🛠️ Tools & Technologies

- Java (JDK 8+)
- MySQL
- JDBC Driver (MySQL Connector/J)
- Spring Tool Suite (STS) or VS Code/IntelliJ

---

## 🗃️ Database Setup

1. Open MySQL and run the following:

```sql
CREATE DATABASE employee_db;

USE employee_db;

CREATE TABLE employees (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    position VARCHAR(100),
    salary DOUBLE
);
