# SQL Database Project - Employee Management

This project demonstrates my ability to design and query a relational database to manage employee information using SQL.  
It includes creating tables, defining relationships, inserting sample data, and running analytical queries.

## Description

The project includes:
- Creating an employee table with fields such as name, ID, department, and salary
- Using foreign key relationships to connect employees with departments
- Inserting sample employee data
- Applying SQL aggregate functions like `COUNT` and `AVG`
- Using `GROUP BY` to generate department-level reports

## Technologies Used
- SQL (Oracle)
- SQL*Plus

## Sample Queries

```sql
-- Count employees per department
SELECT DeptNo, COUNT(*) AS EmployeeCount
FROM Employee
GROUP BY DeptNo;

-- Calculate average salary per department
SELECT DeptNo, AVG(Salary) AS AverageSalary
FROM Employee
GROUP BY DeptNo;

## About Me

This project was developed as part of my practical SQL training during the Makeen Bootcamp.
It reflects my ability to organize data logically, build relationships between tables, and extract insights using SQL queries.
