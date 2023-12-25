# SQL Database Setup

This document provides SQL schema creation queries and data insertion statements for three tables: `Students`, `Courses`, and `Mentors`.

## Schema Creation

### Students Table
```sql
CREATE TABLE Students (
    student_id INT PRIMARY KEY,
    student_name VARCHAR(50),
    email VARCHAR(50),
    phone VARCHAR(15)
);
