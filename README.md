# Level-0--Roadmap
C# .NET, Database & SQL: 3-Month Learning Plan (Level 0)

C# Fundamentals → Database & SQL → OOP

Goal

Build a strong programming foundation in C#, learn relational database design and SQL, then apply Object-Oriented Programming in a complete C# project. The plan includes coding exercises, SQL interview practice, and progress tracking.

Learning Rules
Study each topic on your own and practice until you master it.
Write and understand every solution. Copying a solution without understanding it is not accepted.
Be ready to explain your submitted code or SQL queries during a session or meeting.
Keep solutions in clearly named folders and files.
Add a comment above every exercise containing its number and source.
Push your work regularly to GitHub and update the progress tracker.
Recommended pace: 3 SQL interview questions per week.
Timeline Overview
Sprint	Duration	Track	Focus
1	Week 1–2	C#	Setup, variables, data types, operators, conditions, console I/O
2	Week 3–4	C#	Loops, arrays, strings, methods, exceptions, basic algorithms
3	Week 5–6	Database & SQL	Database concepts, ERD, keys, normalization, CRUD
4	Week 7–8	Database & SQL	Filtering, sorting, functions, grouping, joins
5	Week 9–10	Database & SQL	Subqueries, views, indexes, transactions, procedures, database project
6	Week 11–12	OOP in C#	Classes, inheritance, polymorphism, interfaces, collections, generics, final project
Sprint 1: C# Fundamentals

Goal: Set up the development environment and write basic C# programs confidently.

Topics

Install .NET 8 SDK and Visual Studio 2022 Community or VS Code with C# Dev Kit
Solution and project structure
Variables and data types: int, double, decimal, string, bool, char
Type casting and conversion
Arithmetic, comparison, and logical operators
Console.WriteLine() and Console.ReadLine()
Conditional statements: if, else if, else, switch
Ternary operator
Basic debugging

Required exercises

Topic	Target
Basic	First 50
Data Types	All 11
Conditional Statements	All 25
Sprint 2: C# Problem Solving

Goal: Use loops, arrays, strings, methods, and exception handling to solve programming problems.

Topics

for, while, do-while, foreach, break, continue
Nested loops and patterns
One-dimensional and two-dimensional arrays
Array methods: Sort, Reverse, Max, Min
String methods and string interpolation
Methods, parameters, return types, and overloading
Optional and named parameters
Value parameters, ref, and out
Math and DateTime
Exception handling: try, catch, finally, throw
File handling basics
Linear search, binary search, bubble sort, and selection sort
Big-O introduction

Required exercises

Topic	Target
Basic	51–104
For Loop	All 83
Array	All 41
String	Minimum 20
Function	All 10
Exception Handling	All 13
Searching and Sorting	All 11
Sprint 3: Database Foundations and SQL Basics

Goal: Understand relational databases, design a simple schema, and write CRUD statements.

Topics

Database, DBMS, RDBMS, table, row, and column
Relational model: entity, attribute, and relationship
ERD basics and cardinality
Keys: primary, foreign, candidate, composite, and unique
Converting an ERD into tables
Normalization: 1NF, 2NF, and 3NF
SQL Server and SQL Server Management Studio setup
SQL data types
CREATE DATABASE, CREATE TABLE, ALTER TABLE, DROP TABLE
Constraints: PRIMARY KEY, FOREIGN KEY, UNIQUE, NOT NULL, CHECK, DEFAULT
CRUD: INSERT, SELECT, UPDATE, DELETE

Required practice

 Draw an ERD for a school database
 Convert the ERD into relational tables
 Create the database and tables using SQL
 Add primary keys, foreign keys, and validation constraints
 Insert at least 20 sample records
 Write CRUD queries and save them in Sprint-03-Database-Basics.sql

SQL interview questions

What is the difference between DBMS and RDBMS?
What is the difference between a primary key and a foreign key?
What is normalization, and why is it useful?
Explain 1NF, 2NF, and 3NF.
What is the difference between DELETE, TRUNCATE, and DROP?
What is the difference between CHAR and VARCHAR?
Sprint 4: SQL Querying and Joins

Goal: Retrieve, filter, aggregate, and combine relational data.

Topics

SELECT, aliases, and DISTINCT
WHERE, AND, OR, NOT, IN, BETWEEN, LIKE
IS NULL and IS NOT NULL
ORDER BY, TOP, and pagination basics
Aggregate functions: COUNT, SUM, AVG, MIN, MAX
GROUP BY and HAVING
String, numeric, and date functions
INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN
Self join and cross join
UNION and UNION ALL

Required practice

 Write ten filtering and sorting queries
 Write five aggregate queries
 Write five GROUP BY and HAVING queries
 Write queries using each required join type
 Find records missing a related row using LEFT JOIN
 Save the work in Sprint-04-SQL-Queries.sql

SQL interview questions

What is the difference between WHERE and HAVING?
What is the difference between COUNT(*) and COUNT(column)?
What is the difference between INNER JOIN and LEFT JOIN?
Write a query that returns the highest salary in each department.
Write a query that finds customers who have not placed an order.
Explain the difference between UNION and UNION ALL.
Sprint 5: Advanced SQL and Database Project

Goal: Use advanced SQL features and complete an interview-ready database project.

Topics

Scalar and correlated subqueries
EXISTS and NOT EXISTS
Common Table Expressions (CTEs)
Window functions: ROW_NUMBER, RANK, DENSE_RANK
Views
Indexes and query-performance basics
Stored procedures and user-defined functions
Transactions: BEGIN, COMMIT, ROLLBACK
ACID properties
Triggers overview
Database security and SQL injection awareness
Backup and recovery overview

Project: Student Course Registration Database
Entities: Students, Instructors, Courses, Departments, Enrollments, Grades.

 ERD and normalized relational schema
 Table-creation script with keys and constraints
 Sample-data script
 CRUD queries
 Filtering and aggregate queries
 At least four joins
 At least two subqueries
 One CTE
 One view
 One stored procedure
 One transaction example
 README explaining the schema and how to run the scripts

SQL interview questions

What is the difference between a join and a subquery?
How can duplicate rows be found?
How can the second-highest salary be returned?
What is an index, and what is its trade-off?
What is a transaction?
Explain the ACID properties.
What is the difference between ROW_NUMBER, RANK, and DENSE_RANK?
What is a CTE, and when is it useful?
What is a view?
How can SQL injection risk be reduced?
Sprint 6: Object-Oriented Programming in C#

Goal: Apply OOP principles, collections, and generics in a complete C# application.

Topics

Classes, objects, fields, methods, and properties
Default, parameterized, and copy constructors
this keyword
Encapsulation and access modifiers
static members
Inheritance and the base keyword
Method overloading and overriding
virtual, override, and polymorphism
Abstract classes and interfaces
sealed classes and methods
Composition versus inheritance
List<T>, Dictionary<TKey,TValue>, Queue<T>, Stack<T>, HashSet<T>
Generic methods, generic classes, and constraints
IEnumerable<T> basics
Exception handling and file persistence

Final Project: Student Management System (C# console application)

Person base class with Student and Instructor derived classes
Encapsulated fields and validated properties
Interfaces for searchable and printable entities
Collections to manage students and courses
Generic search or repository component
Exception handling
File-based storage or optional SQL database integration
Reports for students, courses, enrollments, and grades

OOP interview questions

What are the four pillars of OOP?
What is the difference between a class and an object?
What is encapsulation, and why is it useful?
What is the difference between overloading and overriding?
What is the difference between an abstract class and an interface?
What is polymorphism? Provide a C# example.
What is the difference between composition and inheritance?
What is the purpose of generics?
What is the difference between List<T> and an array?
What is the difference between Dictionary<TKey,TValue> and HashSet<T>?
Progress Tracker
Sprint	Checklist
1	Setup · Basic ___/50 · Data Types ___/11 · Conditions ___/25
2	Basic ___/54 · Loops ___/83 · Arrays ___/41 · Strings ___/20+ · Functions ___/10 · Exceptions ___/13 · Algorithms ___/11
3	ERD · Normalized schema · Tables and constraints · CRUD script · Interview questions ___/6
4	Filtering and sorting · Aggregates · Joins · Interview questions ___/6
5	Advanced SQL exercises · Student Course Registration Database · Interview questions ___/10
6	OOP topics · Collections and generics · Student Management System · Interview questions ___/10
