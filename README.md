# 🎨 Creative Arts School - Student Records Database Management System

## 📌 Project Title
Creative Arts School - Student Records Database Management System (DBMS)

## 📝 Description

This project implements a full-featured **Relational Database Management System** using MySQL for managing student records at a Creative Arts School. It is designed to streamline and organize academic data for students, instructors, departments, and courses.

Key features include:

- 📚 Department management  
- 🧑‍🎓 Student profiles and enrollments  
- 👩‍🏫 Instructor records  
- 📖 Course offerings  
- 📅 Attendance tracking  
- 🔐 Role-based access control (Admin, Instructor, Student)  
- 👥 User account management with permissions  

This system ensures data consistency, security, and relational integrity using **foreign keys**, **constraints**, and **ENUM-based roles**.

---

## 🗂️ Database Schema Overview

### Tables:
- **department** – Stores department information  
- **student** – Holds student personal and academic details  
- **instructor** – Manages instructor details  
- **course** – Associates instructors and departments with courses  
- **enrollment** – Tracks which students are enrolled in which courses  
- **attendance** – Records student attendance for each course session  
- **user** – Handles user login credentials and roles  
- **role_permission** – Implements role-based access control

All tables include proper constraints such as `PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`, and `UNIQUE`.

---

## ⚙️ How to Set Up and Run the Project

### Prerequisites:
- ✅ MySQL Server (5.7 or above recommended)
- ✅ MySQL Workbench or any SQL client
- ✅ A MySQL user with privileges to create databases and tables

### Setup Instructions:

1. **Clone or download this project** to your machine.
2. Open your MySQL client (e.g., MySQL Workbench).
3. Create a new database:
   ```sql
   CREATE DATABASE studentrecords;
   USE studentrecords;
