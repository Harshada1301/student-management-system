# Student Management System

## Project Overview

The Student Management System is a relational database project developed using **MySQL and SQL** to manage student, course, and enrollment records efficiently.

The project demonstrates practical SQL concepts such as CRUD operations, JOINs, aggregate functions, GROUP BY, HAVING, CASE expressions, sorting, filtering, and custom reporting.

## Technologies Used

* MySQL
* SQL

## Database Structure

The database contains three main tables:

### 1. Students

Stores student personal and contact information.

**Columns:**

* student_id
* first_name
* last_name
* email
* phone
* gender
* date_of_birth
* city

### 2. Courses

Stores course-related information.

**Columns:**

* course_id
* course_name
* department
* duration_months
* fees

### 3. Enrollments

Stores student enrollment and academic information.

**Columns:**

* enrollment_id
* student_id
* course_id
* enrollment_date
* marks
* grade
* status

## SQL Concepts Implemented

* Database and table creation
* Primary Keys
* Foreign Keys
* Constraints
* INSERT operations
* SELECT queries
* UPDATE operations
* DELETE operations
* INNER JOIN
* LEFT JOIN
* WHERE clause
* ORDER BY
* GROUP BY
* HAVING
* COUNT()
* AVG()
* ROUND()
* CASE expression
* Custom reports

## Key Reports

The project generates several useful reports, including:

* Top 3 students based on marks
* Active students report
* City-wise student count
* Course-wise student count
* Course-wise average marks
* Grade-wise student count
* Status-wise enrollment count
* Course performance report
* Student performance classification

## Project Highlights

* Designed a relational database with connected tables.
* Maintained relationships between students, courses, and enrollments using foreign keys.
* Performed CRUD operations for data management.
* Used JOINs to combine information from multiple tables.
* Used aggregate functions and GROUP BY for analytical reports.
* Used HAVING to filter grouped results.
* Used CASE expressions to classify student performance.

## How to Run

1. Install MySQL.
2. Open MySQL Workbench.
3. Open `student_management_system.sql`.
4. Execute the SQL script.
5. The `student_management` database and required tables will be created automatically.
6. Run the queries to explore the database and reports.

## Project Structure

```text
Student-Management-System/
│
├── student_management_system.sql
└── README.md
```

## Author

**Harshada Borse**

Computer Engineering Graduate | Aspiring Data Analyst / Data Scientist
