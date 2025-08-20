# Library-Management-System
📚 A SQL-based Library Management System that manages branches, employees, customers, and books. It tracks book issues/returns, maintains customer and employee records, and provides insights through queries such as available books, salary reports, branch employee counts, and book categories.

📌 Project Overview

The Library Management System is a SQL-based project designed to manage and organize information about branches, employees, customers, books, and their issue/return status.
It demonstrates how relational databases can be used to handle common library operations such as book issuance, returns, employee management, and customer records.

🗄️ Database Schema

The system consists of the following tables:

Branch – Stores branch details (branch number, manager, address, contact)

Employee – Stores employee information (ID, name, position, salary, branch)

Customer – Stores customer details (ID, name, address, registration date)

Books – Stores information about books (ISBN, title, category, rental price, author, publisher, availability)

IssueStatus – Tracks books issued to customers with issue date and book details

ReturnStatus – Tracks returned books with return date and customer details

📂 Features Implemented

✔️ Create and manage multiple library branches
✔️ Maintain employee records with salaries and roles
✔️ Store customer registration details
✔️ Track book availability, categories, and rental prices
✔️ Manage book issues and returns
✔️ Execute queries for insights such as:

Available books and their rental prices

Employees earning above a certain salary

Customers who issued books in a specific time period

Branches with more than 5 employees

Book counts by category

⚙️ Queries Included

The project includes SQL queries to perform real-world tasks, such as:

Retrieve all available books with category and rental price

List employees by salary (descending order)

Find customers who issued specific books

Count books per category

Get employees with salaries above ₹50,000

Identify customers registered before a date but haven’t issued books

Count employees per branch

Find customers who issued books in June 2023

Retrieve book titles from the History category

Display branches with more than 5 employees

🚀 How to Run
1️⃣ Clone this repository
git clone https://github.com/your-username/library-management-system.git
cd library-management-system

2️⃣ Open MySQL and execute the SQL script
source LibraryManagementSystem.sql;

3️⃣ Run queries

You can execute any of the provided queries to test functionality.

🛠 Tech Stack

MySQL / SQL

Relational Database Management
