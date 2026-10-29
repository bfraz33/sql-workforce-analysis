# SQL Workforce Analysis

#Overview

This project uses SQL to analyze workforce data, employee salaries, department structures, and office locations. The goal is to answer business questions using SQL queries and demonstrate practical database querying.

The project is built in SSMS using the `hcm` schema.

# Objectives

- Analyze employee and department data.
- Explore salary ranges and workforce distribution.
- Connect employee, department, and location information.
- Identify departments with no employees.
- Practice writing queries that answer real-world business questions.

# SQL Skills Demonstrated

- `SELECT` statements
- Filtering with `WHERE`
- Range filtering with `BETWEEN`
- Aggregate functions such as `COUNT`, `AVG`, `SUM`, `MIN`, and `MAX`
- `INNER JOIN`
- `LEFT JOIN`
- `FULL JOIN`
- Handling `NULL` values
- Table aliases and join conditions

# Database Tables

| Table | Purpose |
|---|---|
| `hcm.employees` | Employee information, including IDs and salaries |
| `hcm.departments` | Department information and department locations |
| `hcm.locations` | Office location information, including cities |

# Business Questions

This project explores questions such as:

1. How many employees work in each department?
2. Which departments have no employees?
3. What is the average salary by department?
4. Which employees earn between $50,000 and $80,000, and in which cities are their departments located?
5. How are employees distributed across departments and locations?
6. How can a full join identify unmatched employee and department records?

# Tools Used

- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- Git
- GitHub

# Project Structure

```text
SQL-Workforce-Analysis/
├── README.md
├── queries/
│   ├── 01_employee_analysis.sql
│   ├── 02_department_analysis.sql
│   ├── 03_salary_analysis.sql
│   ├── 04_location_analysis.sql
│   └── 05_join_analysis.sql
└── screenshots/
```

*The folder and file names above are a suggested structure. Update them to match the files in your repository.*

# What I Learned

Through this project, I am developing my ability to write SQL queries, join relational tables, filter records, analyze workforce data, and translate business questions into database queries.

I am using this project as part of my continued development in SQL, database management, and data analysis.

# Future Improvements

- Add more advanced aggregate queries.
- Practice subqueries and Common Table Expressions (CTEs).
- Add window functions and ranking analysis.
- Improve query readability and documentation.
- Incorporate data visualizations as the project expands.

