# SQL-Employee-Management-System
📊 SQL Project: Employee & Payroll Management System

🔹 Project Overview

This project focuses on building a complete SQL-based Employee and Payroll Management System. The goal was to design a relational database, import real-world data from Excel files, enforce data integrity through constraints, and generate business insights using SQL queries.

🔹 Data Import

Imported raw datasets from Excel files containing information about employees, job departments, salaries, bonuses, leaves, payroll, and qualifications.

Cleaned and transformed the data to match the database schema.

Loaded the datasets into MySQL tables using import tools.

🔹 Database Design

Created normalized tables for:

JobDepartment (Job roles, salary ranges, department names)

SalaryBonus (Salary, annual pay, bonuses)

Employee (Employee details, job references, login info)

Qualification (Employee qualifications, requirements)

Leaves (Leave records and reasons)

Payroll (Payroll records, total salary, deductions)

Defined Primary Keys, Foreign Keys, and Constraints:

Cascading updates/deletes to maintain integrity.

Unique constraints (like emails).

ON DELETE SET NULL where necessary.

🔹 SQL Queries & Analysis
1. Employee Insights

Counted total employees and unique employees.

Found departments with the highest workforce.

Calculated average salary per department.

Listed top 5 highest-paid employees.

Computed total company salary expenditure.

2. Job Role & Department Analysis

Found number of job roles in each department.

Analyzed salary ranges per department.

Identified highest-paying job roles.

Summed salary allocation per department.

3. Qualification & Skills Analysis

Counted employees with at least one qualification.

Identified positions requiring most qualifications.

Ranked employees with highest number of qualifications.

4. Leave & Absence Patterns

Analyzed leaves per year.

Found average leave days per department.

Identified employees with most leaves.

Counted total leave days company-wide.

Correlated leave days with payroll amounts.

5. Payroll & Compensation

Calculated total monthly payroll.

Found average bonus per department.

Identified department with highest total bonuses.

Compared before vs after deductions in payroll.

6. Employee Growth & Promotions

Analyzed yearly promotions based on bonus allocation.

Tracked employee growth patterns.

🔹 Key Features & Outcomes

End-to-End Pipeline: Imported Excel → Database Design → SQL Queries → Business Insights.

Data Integrity: Enforced with constraints, relationships, and proper keys.

Business Insights: Gave actionable results on workforce, payroll, leaves, and qualifications.

Scalability: The schema can easily expand with more datasets.

🔹 Tools & Technologies Used

SQL (MySQL) – Database design & queries

Excel – Data source

MySQL Workbench / CLI – For schema creation & query execution

🔹 Final Result

The project successfully simulated a real-world HR & Payroll Management System where employee, salary, and performance data were systematically stored, managed, and analyzed. Using SQL, I generated valuable business insights that can help organizations in decision-making, payroll optimization, and workforce planning.
