# 📚 Library Database Management System

## 📌 Project Description

This is a Library Management System developed using Java and MySQL.
The project helps manage books, students, and issue/return records efficiently.

It is designed to automate basic library operations and reduce manual work.

---

## 💻 Technologies Used

* Java
* MySQL
* JDBC (Java Database Connectivity)
* NetBeans IDE

---

## ✨ Features

* Add new books to the library
* Manage student records
* Issue books to students
* Return books and update records
* Login system for authentication
* Store and retrieve data using database

---

## 🗄️ Database Setup

This project uses a MySQL database.

### Steps to setup database:

1. Open MySQL Workbench or phpMyAdmin
2. Create a new database:

   ```
   CREATE DATABASE library;
   ```
3. Import the provided SQL file:

   * File name: `library_db.sql`

OR run:

```
USE library;
SOURCE path_to/library_db.sql;
```

---

## 🚀 How to Run the Project

1. Open the project in NetBeans or any Java IDE

2. Configure database connection in code:

   * URL: `jdbc:mysql://localhost:3306/library`
   * Username: your MySQL username
   * Password: your MySQL password

3. Run the main Java file

---

## 📂 Project Structure

* `src/` → Source code (Java files + images)
* `test/` → Test files (optional)
* `library_db.sql` → Database file

---

## 🎯 Future Improvements

* Add GUI enhancements
* Add fine calculation for late returns
* Add admin dashboard
* Improve security and authentication

---

## 🙋‍♀️ Author

SHIFRA PANWAR

---

## ⭐ Note

This project is created for learning purposes and demonstrates basic DBMS concepts using Java and MySQL.
