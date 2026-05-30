# Student Record Management System

JavaFX + JDBC + PostgreSQL CRUD application for managing student records.

## Features
- Add student
- Update student
- Delete student
- View all students in table
- Clear input fields

## How to Run
1. Create database in pgAdmin: `studentdb`
2. Create table:
CREATE TABLE students ( id SERIAL PRIMARY KEY, name VARCHAR(100), course VARCHAR(50), year_level VARCHAR(20) );
3. Update password in `DBConnection.java`
4. Run `MainApp.java`

## Tools Used
- Java 21
- JavaFX
- PostgreSQL
- JDBC

## Author
Patricia S. Ardita | BSIT 2-1
