
# C# .NET, Database & SQL — 3-Month Learning and Interview Plan

> **6-Sprint Learning Plan** | C# Fundamentals → Database & SQL → OOP

## Goal

Build a strong programming foundation in C#, learn relational database design and SQL, then apply Object-Oriented Programming in a complete C# project. The plan also includes coding exercises, SQL interview practice, progress tracking, and submission guidance.

## Learning Rules

* Write and understand every solution. Copying a solution without understanding it is not accepted.
* Be ready to explain submitted code or SQL queries during a session or meeting.
* Keep solutions in clearly named folders and files.
* Add a comment above every exercise containing its number and source.
* Push work regularly to GitHub and update the progress tracker.
* Recommended interview pace: **3 SQL interview questions per week**.

---

## Updated Timeline Overview

| **Sprint** | **Duration** | **Main Track** | **Focus**                                                                                             |
| ---------- | ------------ | -------------- | ----------------------------------------------------------------------------------------------------- |
| Sprint 1   | Week 1–2     | C#             | Setup, variables, data types, operators, conditions, console I/O                                      |
| Sprint 2   | Week 3–4     | C#             | Loops, arrays, strings, methods, exceptions, and basic algorithms                                     |
| Sprint 3   | Week 5–6     | Database & SQL | Database concepts, ERD, tables, keys, normalization, and CRUD                                         |
| Sprint 4   | Week 7–8     | Database & SQL | Filtering, sorting, functions, grouping, and joins                                                    |
| Sprint 5   | Week 9–10    | Database & SQL | Subqueries, views, indexes, transactions, procedures, and interviews                                  |
| Sprint 6   | Week 11–12   | OOP in C#      | Classes, encapsulation, inheritance, polymorphism, abstraction, interfaces, collections, and generics |

---

# Sprint 1 — C# Fundamentals

**Duration:** Week 1–2

**Goal:** Set up the development environment and write basic C# programs confidently.

## Topics

* Install .NET 8 SDK
* Install Visual Studio 2022 Community or VS Code with C# Dev Kit
* Solution and Project structure
* Variables and data types: `int`, `double`, `decimal`, `string`, `bool`, `char`
* Type casting and conversion
* Arithmetic, comparison, and logical operators
* `Console.WriteLine()` and `Console.ReadLine()`
* Conditional statements: `if`, `else if`, `else`, `switch`
* Ternary operator
* Basic debugging

## Required Exercises

| **Topic**              | **Target** |
| ---------------------- | ---------- |
| Basic                  | First 50   |
| Data Types             | All 11     |
| Conditional Statements | All 25     |

---

# Sprint 2 — C# Problem Solving

**Duration:** Week 3–4

**Goal:** Use loops, arrays, strings, methods, and exception handling to solve programming problems.

## Topics

* `for`, `while`, `do-while`, `foreach`
* `break` and `continue`
* Nested loops and patterns
* One-dimensional and two-dimensional arrays
* Array methods: `Sort`, `Reverse`, `Max`, `Min`
* String methods and string interpolation
* Methods, parameters, return types, and overloading
* Optional and named parameters
* Value parameters, `ref`, and `out`
* `Math` and `DateTime`
* Exception handling: `try`, `catch`, `finally`, `throw`
* File handling basics
* Linear search, binary search, bubble sort, and selection sort
* Big-O introduction

## Required Exercises

| **Topic**             | **Target** |
| --------------------- | ---------- |
| Basic                 | 51–104     |
| For Loop              | All 83     |
| Array                 | All 41     |
| String                | Minimum 20 |
| Function              | All 10     |
| Exception Handling    | All 13     |
| Searching and Sorting | All 11     |

---

# Sprint 3 — Database Foundations and SQL Basics

**Duration:** Week 5–6

**Goal:** Understand relational databases, design a simple schema, and write CRUD statements.

## Topics

* Database, DBMS, RDBMS, table, row, and column
* Relational database model
* Entity, attribute, and relationship
* ERD basics and cardinality
* Database keys: primary, foreign, candidate, composite, and unique
* Converting an ERD into tables
* Normalization: 1NF, 2NF, and 3NF
* Install SQL Server and SQL Server Management Studio, or use an approved SQL playground
* SQL data types
* `CREATE DATABASE`, `CREATE TABLE`, `ALTER TABLE`, `DROP TABLE`
* Constraints: `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `NOT NULL`, `CHECK`, `DEFAULT`
* CRUD: `INSERT`, `SELECT`, `UPDATE`, `DELETE`

## Required Practice

* Draw an ERD for a school database.
* Convert the ERD into relational tables.
* Create the database and tables using SQL.
* Add primary keys, foreign keys, and validation constraints.
* Insert at least 20 sample records.
* Write CRUD queries and save them in `Sprint-03-Database-Basics.sql`.

## SQL Interview Questions

1. What is the difference between DBMS and RDBMS?
2. What is the difference between a primary key and a foreign key?
3. What is normalization, and why is it useful?
4. Explain 1NF, 2NF, and 3NF.
5. What is the difference between `DELETE`, `TRUNCATE`, and `DROP`?
6. What is the difference between `CHAR` and `VARCHAR`?

---

# Sprint 4 — SQL Querying and Joins

**Duration:** Week 7–8

**Goal:** Retrieve, filter, aggregate, and combine relational data.

## Topics

* `SELECT`, aliases, and `DISTINCT`
* `WHERE`, comparison operators, `AND`, `OR`, `NOT`
* `IN`, `BETWEEN`, `LIKE`, wildcards
* `IS NULL` and `IS NOT NULL`
* `ORDER BY`, `TOP`, and pagination basics
* Aggregate functions: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`
* `GROUP BY` and `HAVING`
* String, numeric, and date functions
* `INNER JOIN`
* `LEFT JOIN`
* `RIGHT JOIN`
* `FULL OUTER JOIN`
* Self join and cross join
* `UNION` and `UNION ALL`

## Required Practice

* Write ten filtering and sorting queries.
* Write five aggregate queries.
* Write five `GROUP BY` and `HAVING` queries.
* Write queries using each required join type.
* Find records missing a related row using `LEFT JOIN`.
* Save the work in `Sprint-04-SQL-Queries.sql`.

## SQL Interview Questions

1. What is the difference between `WHERE` and `HAVING`?
2. What is the difference between `COUNT(*)` and `COUNT(column)`?
3. What is the difference between `INNER JOIN` and `LEFT JOIN`?
4. Write a query that returns the highest salary in each department.
5. Write a query that finds customers who have not placed an order.
6. Explain the difference between `UNION` and `UNION ALL`.

---

# Sprint 5 — Advanced SQL and Database Project

**Duration:** Week 9–10

**Goal:** Use advanced SQL features and complete an interview-ready database project.

## Topics

* Scalar and correlated subqueries
* `EXISTS` and `NOT EXISTS`
* Common Table Expressions (CTEs)
* Window functions: `ROW_NUMBER`, `RANK`, `DENSE_RANK`
* Views
* Indexes and query-performance basics
* Stored procedures and user-defined functions
* Transactions: `BEGIN`, `COMMIT`, `ROLLBACK`
* ACID properties
* Triggers overview
* Database security and SQL injection awareness
* Backup and recovery overview

## Database Mini Project

Build a **Student Course Registration Database** containing:

* Students
* Instructors
* Courses
* Departments
* Enrollments
* Grades

### Project Requirements

* ERD and normalized relational schema
* Table-creation script with keys and constraints
* Sample-data script
* CRUD queries
* Filtering and aggregate queries
* At least four joins
* At least two subqueries
* One CTE
* One view
* One stored procedure
* One transaction example
* README explaining the schema and how to run the scripts

## SQL Interview Questions

1. What is the difference between a join and a subquery?
2. How can duplicate rows be found?
3. How can the second-highest salary be returned?
4. What is an index, and what is its trade-off?
5. What is a transaction?
6. Explain the ACID properties.
7. What is the difference between `ROW_NUMBER`, `RANK`, and `DENSE_RANK`?
8. What is a CTE, and when is it useful?
9. What is a view?
10. How can SQL injection risk be reduced?

---

# Sprint 6 — Object-Oriented Programming in C#

**Duration:** Week 11–12

**Goal:** Apply OOP principles, collections, and generics in a complete C# application connected to the knowledge gained from the database sprints.

## Topics

* Classes and objects
* Fields, methods, and properties
* Default, parameterized, and copy constructors
* `this` keyword
* Encapsulation and access modifiers
* `static` members
* Inheritance and the `base` keyword
* Method overloading and overriding
* `virtual`, `override`, and polymorphism
* Abstract classes and abstract methods
* Interfaces and multiple-interface implementation
* `sealed` classes and methods
* Composition versus inheritance
* `List<T>`, `Dictionary<TKey,TValue>`, `Queue<T>`, `Stack<T>`, `HashSet<T>`
* Generic methods, generic classes, and constraints
* `IEnumerable<T>` basics
* Exception handling and file persistence

## Final Project — Student Management System

Build a C# console application that applies the complete track:

* `Person` base class
* `Student` and `Instructor` derived classes
* Encapsulated fields and validated properties
* Interfaces for searchable and printable entities
* Collections to manage students and courses
* Generic search or repository component
* Exception handling
* File-based storage or optional SQL database integration
* Reports for students, courses, enrollments, and grades

## OOP Interview Questions

1. What are the four pillars of OOP?
2. What is the difference between a class and an object?
3. What is encapsulation, and why is it useful?
4. What is the difference between overloading and overriding?
5. What is the difference between an abstract class and an interface?
6. What is polymorphism? Provide a C# example.
7. What is the difference between composition and inheritance?
8. What is the purpose of generics?
9. What is the difference between `List<T>` and an array?
10. What is the difference between `Dictionary<TKey,TValue>` and `HashSet<T>`?

---

## Recommended Repository Structure

```text
Level-0_plan-updated/
├── README.md
├── Sprint-01-CSharp-Fundamentals/
├── Sprint-02-CSharp-Problem-Solving/
├── Sprint-03-Database-Foundations/
├── Sprint-04-SQL-Queries/
├── Sprint-05-Advanced-SQL/
├── Sprint-06-OOP/
└── Projects/
    ├── Student-Course-Database/
    └── Student-Management-System/
```

## Progress Tracker

### Sprint 1 — C# Fundamentals

* Setup completed
* Basic exercises: ___/50
* Data Types: ___/11
* Conditions: ___/25

### Sprint 2 — C# Problem Solving

* Basic exercises: ___/54
* Loops: ___/83
* Arrays: ___/41
* Strings: ___/20 minimum
* Functions: ___/10
* Exceptions: ___/13
* Algorithms: ___/11

### Sprint 3 — Database Foundations

* ERD completed
* Normalized schema completed
* Tables and constraints completed
* CRUD script completed
* SQL interview questions: ___/6

### Sprint 4 — SQL Queries and Joins

* Filtering and sorting queries completed
* Aggregate queries completed
* Joins completed
* SQL interview questions: ___/6

### Sprint 5 — Advanced SQL

* Advanced SQL exercises completed
* Student Course Registration Database completed
* SQL interview questions: ___/10

### Sprint 6 — OOP

* OOP topics completed
* Collections and generics completed
* Student Management System completed
* OOP interview questions: ___/10

---

## Final Mock Interview

* Explain one C# fundamentals solution without running it.
* Solve one array or string problem in 30–40 minutes.
* Explain time and space complexity.
* Design a small relational database and explain the relationships.
* Write three SQL queries, including a join, aggregation, and subquery.
* Answer five database and five OOP questions.
* Demonstrate the final project and explain design decisions.

---

*C# .NET, Database & SQL Track — Level 0 | 3-Month Plan*
