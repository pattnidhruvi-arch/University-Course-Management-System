# 🎓 University Course Management System

## 📌 Project Title

**University Course Management System – SQL Final Project**

---

## 📖 Project Overview

The University Course Management System is a relational database project developed using SQL and MySQL.

The main purpose of this project is to manage and organize university-related information such as students, courses, instructors, enrollments, and academic departments.

This project demonstrates practical implementation of SQL concepts including database creation, table creation, CRUD operations, joins, subqueries, aggregate functions, filtering, grouping, sorting, string manipulation, date functions, CASE expressions, and window functions.

The project is designed to provide an organized and efficient way to store, retrieve, update, and analyze university course management data.

---

## 🎯 Objectives

The main objectives of this project are:

- To design a relational database for a university.
- To store student information efficiently.
- To maintain course and department information.
- To manage instructor information.
- To track student course enrollments.
- To perform CRUD operations.
- To retrieve meaningful information using SQL queries.
- To apply joins and subqueries.
- To use aggregate and analytical functions.
- To demonstrate advanced SQL concepts.
- To analyze university data using SQL.

---

## 🗄️ Database Name

```text
UniversityCourseManagement
# University Course Management System

## Project Overview

The University Course Management System is a MySQL database project designed to manage university departments, students, courses, instructors, and student enrollments.

## Database Name

`universitycoursemanagement`

## Database Tables

The database contains the following tables:

### 1. Departments
Stores university department information.

- DepartmentID
- DepartmentName

Sample Departments:
- Computer Science
- Mathematics

### 2. Students
Stores student information.

- StudentID
- FirstName
- LastName
- Email
- BirthDate
- EnrollmentDate

### 3. Courses
Stores course details.

- CourseID
- CourseName
- DepartmentID
- Credits

Sample Courses:
- Introduction to SQL
- Data Structures
- Calculus

### 4. Instructors
Stores instructor information.

- InstructorID
- FirstName
- LastName
- Email
- DepartmentID

### 5. Enrollments
Stores student course enrollment information.

- EnrollmentID
- StudentID
- CourseID
- EnrollmentDate

## Database Relationships

- Departments → Courses
- Departments → Instructors
- Students → Enrollments
- Courses → Enrollments

Primary keys and foreign keys are used to maintain data integrity and establish relationships between tables.

## Sample Data

### Departments
| DepartmentID | DepartmentName |
|---|---|
| 1 | Computer Science |
| 2 | Mathematics |

### Students
| StudentID | FirstName | LastName |
|---|---|---|
| 1 | John | Doe |
| 2 | Jane | Smith |

### Courses
| CourseID | CourseName | DepartmentID | Credits |
|---|---|---|---|
| 101 | Introduction to SQL | 1 | 3 |
| 102 | Data Structures | 1 | 4 |
| 103 | Calculus | 2 | 3 |

### Instructors
| InstructorID | FirstName | LastName | DepartmentID |
|---|---|---|---|
| 1 | Alice | Johnson | 1 |
| 2 | Bob | Lee | 2 |

### Enrollments
| EnrollmentID | StudentID | CourseID | EnrollmentDate |
|---|---|---|---|
| 1 | 1 | 101 | 2020-08-01 |
| 2 | 2 | 102 | 2023-08-01 |
| 3 | 1 | 102 | 2020-08-01 |

## Technologies Used

- MySQL
- phpMyAdmin
- SQL

## Features

- Department Management
- Student Management
- Course Management
- Instructor Management
- Student Enrollment Management
- Primary Key and Foreign Key Relationships
- Data Integrity using Constraints

## Conclusion

This project demonstrates the design and implementation of a relational database for managing university courses, students, instructors, departments, and enrollments using MySQL.
