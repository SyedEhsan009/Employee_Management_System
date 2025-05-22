README Description for "Employee Management System - SQL Project" Project Title: Employee Management System – SQL Project

Project Overview

The Employee Management System provides a relational database structure to efficiently store, retrieve, and analyze employee information. It is ideal for learning and demonstrating SQL concepts such as table creation, relationships (foreign keys), data insertion, and advanced querying.

Database Structure

The project consists of four main tables:

Departments: Stores department details.

Fields: DeptID, DeptName

Employees: Contains employee personal and job-related information.

Fields: EmpID, FirstName, LastName, Gender, DeptID (foreign key), Salary, JoiningDate

Attendance: Tracks daily attendance status of employees.

Fields: AttendanceID, EmpID (foreign key), Date, Status (Present, Absent, Leave)

Performance: Records annual performance ratings and remarks for employees.

Fields: RecordID, EmpID (foreign key), Year, Rating (1-5), Remarks

Sample Data

The project includes sample data for each table:

Four departments (HR, IT, Sales, Finance)

Six employees with varied roles, salaries, and joining dates

Attendance records for a sample month

Performance ratings for each employee

Key Features & SQL Queries

The project demonstrates several advanced SQL queries and analyses:

Department-wise Average Salary: Calculates and ranks the average salary by department.

Employee List with Department Names: Joins employee and department data for reporting.

Top Attendance in Last 30 Days: Identifies the employee with the highest attendance in the recent month.

Top Performers by Year: Lists employees with the highest performance ratings for the latest year.

Average Performance Rating per Department: Aggregates and ranks departments by average employee rating.

Salary Categorization: Classifies employees into salary bands (good, medium, normal, low) using CASE statements.

Departmental Salary Ranking: Ranks employees by salary within each department using window functions.

Usage

The SQL file can be run in any MySQL-compatible environment.

All tables are created from scratch, with existing tables dropped for a clean setup.

Sample data is inserted for immediate testing and analysis.

Example queries are provided for direct execution and learning purposes.

Learning Outcomes

Understanding of relational database design and normalization

Practical experience with SQL DDL (CREATE, DROP) and DML (INSERT, SELECT)

Use of JOINs, GROUP BY, aggregate functions, window functions (RANK), and CASE statements

Real-world HR data analysis scenarios

