# Joins and Set Operations
© ExploreAI Academy

## Overview
This project focuses on mastering SQL operations involving Joins and Set Operations to solve real-world data manipulation and querying tasks. By completing this exercise, learners will understand how to combine data from multiple sources using both row-wise and column-wise operations in SQL.

## Learning Objectives
In this exercise, you will:

- Understand and use different types of SQL Joins:

  - `INNER JOIN`

- Utilize SQL Set Operations:

  - `UNION`
  
- Learn the conceptual difference between:

  - Joins (column-wise combination based on keys)
  
  - Set operations (row-wise combination based on identical structure)

## Prerequisites
- Basic knowledge of SQL syntax and relational databases.

- SQL environment such as:

  - PostgreSQL / MySQL / SQLite
  
  - DBMS tools like DBeaver, pgAdmin, MySQL Workbench
  

## Folder Structure
```
joins-set-operations/
│
├── data/
│   ├── employees.sql
│   ├── departments.sql
│   └── salaries.sql
│
├── solutions/
│   ├── joins_queries.sql
│   ├── set_operations.sql
│
├── README.md
└── joins_set_operations_notebook.ipynb  (optional Jupyter notebook for guided exercises)
```

## Tasks
### 🧩 Join Operations
Write SQL queries using:

  - INNER JOIN to find common records between tables.
  
  - LEFT JOIN to include unmatched rows from the left table.
  
  - RIGHT JOIN to include unmatched rows from the right table.
  
  - FULL OUTER JOIN to get all records from both tables, matched and unmatched.
  
  - SELF JOIN to find relationships within a single table (e.g., employee-manager relationships).

## 🧪 Set Operations
Perform set operations using:

  - UNION and UNION ALL to merge rows from two datasets.
  
  - INTERSECT to find common rows between tables.
  
  - MINUS / EXCEPT to find differences in datasets.

# Expected Output
  - A series of well-commented SQL scripts that execute various joins and set operations.
  
  - Output tables demonstrating correct use of row-wise and column-wise data merging.

# Additional Resources
  - [W3Schools SQL Joins](https://www.w3schools.com/sql/sql_join.asp)  
  - [PostgreSQL Set Operations](https://www.postgresql.org/docs/current/queries-union.html)  
  - [Mode SQL Tutorial](https://mode.com/sql-tutorial)  
  - [SQLite Joins](https://www.sqlitetutorial.net/sqlite-joins/)

# Author
ExploreAI Academy Learner
For more SQL projects, visit [ExploreAI Academy](https://www.explore.ai/about-exploreai)
