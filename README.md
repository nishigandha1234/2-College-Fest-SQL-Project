# 🎉 College Fest Database Management System

A comprehensive **SQL-based Database Management System** designed to manage and organize all major activities involved in a college fest, including departments, students, events, organizers, venues, and participant details.

This project demonstrates strong fundamentals of **relational database design** and **SQL querying**, making it ideal for **academic submission, GitHub portfolio, and interview discussions**.

---

## 📌 Project Overview

College fests involve multiple departments, events, students, organizers, and venues. Managing all this data manually can be inefficient and error-prone.  
This project solves that problem by providing a **structured relational database** that ensures:

- Proper data organization  
- Data consistency using constraints  
- Easy retrieval of information using SQL queries  

The system allows tracking:
- Which department organizes which event
- Which students participate in which events
- Event venues and organizers
- Participation details and statistics

---

## 🎯 Objectives of the Project

- To design a **normalized relational database**
- To understand and implement **Primary & Foreign Key relationships**
- To apply **SQL joins and aggregate functions**
- To retrieve meaningful insights from data using queries
- To gain hands-on experience with **MySQL & MySQL Workbench**

---

## 🛠 Technologies Used

- **MySQL** – Database creation and management  
- **MySQL Workbench** – Writing, executing, and testing SQL scripts  

---

## 🗄 Database Schema & Tables

The database consists of the following tables:

### 1️⃣ Department
Stores department details involved in the fest.
- department_id (Primary Key)
- department_name

### 2️⃣ Student
Stores student information.
- student_id (Primary Key)
- student_name
- department_id (Foreign Key)

### 3️⃣ Organizer
Contains organizer details.
- organizer_id (Primary Key)
- organizer_name
- department_id (Foreign Key)

### 4️⃣ Event
Stores event-related information.
- event_id (Primary Key)
- event_name
- organizer_id (Foreign Key)
- venue_id (Foreign Key)

### 5️⃣ Venue
Contains venue details.
- venue_id (Primary Key)
- venue_name
- capacity

### 6️⃣ Participation
Maintains participation records.
- participation_id (Primary Key)
- student_id (Foreign Key)
- event_id (Foreign Key)

---

## 🔍 SQL Concepts & Features Used

- `CREATE DATABASE`, `CREATE TABLE`
- Primary Key & Foreign Key Constraints
- Data Integrity & Relationships
- `INSERT`, `UPDATE`, `DELETE`
- Joins:
  - `INNER JOIN`
  - `LEFT JOIN`
- Aggregate Functions:
  - `COUNT()`
  - `SUM()`
  - `AVG()`
- `GROUP BY` and `HAVING`
- Subqueries (if applicable)

---

## ▶ How to Run the Project

Follow these steps to execute the project successfully:

1. Open **MySQL Workbench**
2. Create a new SQL tab
3. Execute:
   - `schema.sql` → Creates database and tables
4. Execute:
   - `insert_data.sql` → Inserts sample records
5. Execute:
   - `queries.sql` → Run queries to retrieve insights

✔ Make sure MySQL server is running before execution.

---

## 📊 Sample Queries Included

- List all events with their organizers and venues  
- Find total participants in each event  
- Display students participating in multiple events  
- Count events organized by each department  
- Retrieve venue-wise event allocation  

---

## 📁 Project Structure
College-Fest-Database-Management-System/
│
├── schema.sql
├── insert_data.sql
├── queries.sql
└── README.md

---

## 🎓 Project Type

- **Academic SQL Mini Project**
- Suitable for:
  - College submission
  - GitHub portfolio
  - SQL interview preparation

---

## 🚀 Future Enhancements

- Add triggers and stored procedures
- Implement views for reporting
- Add user roles and permissions
- Integrate with a frontend application
- Add event scheduling and timing features

---

## 👤 Author

**Nishigandha Kakade**  
Aspiring Software Developer | Java & SQL Enthusiast  

📌 GitHub: [nishigandha1234](https://github.com/nishigandha1234)

---

⭐ If you like this project, feel free to star the repository!
