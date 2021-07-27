# SQL-Tutorials ❤️

![](https://img.shields.io/github/languages/count/gowthamrajk/SQL-Tutorials)   ![](https://img.shields.io/github/languages/top/gowthamrajk/SQL-Tutorials)

In this module, I will be updating the topic wise SQL tutorial notes which is very useful for a fresher to start with MYSQL from basics

# Introduction 👋

- SQL stands for Structured Query Language. 
- This tutorial will give you a quick start to SQL. 
- It covers most of the topics required for a basic understanding of SQL and to get a feel of how it works.

# A Brief History of SQL ⌚

**1970** − Dr. Edgar F. "Ted" Codd of IBM is known as the father of relational databases. He described a relational model for databases.

**1974** − Structured Query Language appeared.

**1978** − IBM worked to develop Codd's ideas and released a product named System/R.

**1986** − IBM developed the first prototype of relational database and standardized by ANSI. The first relational database was released by Relational Software which later came to be known as Oracle.

# Why to Learn SQL 🤔

- SQL is the standard language for Relational Database System. 
- All the Relational Database Management Systems (RDMS) like MySQL, MS Access, Oracle, Sybase, Informix, Postgres and SQL Server use SQL as their standard database language.

Also, they are using different dialects, such as −

### 1) MS SQL Server using T-SQL,
### 2) Oracle using PL/SQL,
### 3) MS Access version of SQL is called JET SQL (native format) etc.

# Features of MYSQL 🚀

High Performance
High Availability
Database mirroring
Database snapshots
CLR integration
Service Broker
DDL triggers
Ranking functions
Row version-based isolation levels
XML integration
TRY...CATCH
Database Mail

# Applications of SQL ✔️

- SQL is one of the most widely used query language over the databases.
- I'm going to list few of them here:

### - Allows users to access data in the relational database management systems.

### - Allows users to describe the data.

### - Allows users to define the data in a database and manipulate that data.

### - Allows to embed within other languages using SQL modules, libraries & pre-compilers.

### - Allows users to create and drop databases and tables.

### - Allows users to create view, stored procedure, functions in a database.

### - Allows users to set permissions on tables, procedures and views.

# SQL Process ⌛

- When you are executing an SQL command for any RDBMS, the system determines the best way to carry out your request and SQL engine figures out how to interpret the task.
- There are various components included in this process.
These components are −

**1) Query Dispatcher**

**2) Optimization Engines**

**3) Classic Query Engine**

**4) SQL Query Engine, etc.**

**5) A classic query engine handles all the non-SQL queries, but a SQL query engine won't handle logical files.**

![image](https://user-images.githubusercontent.com/43011442/127163328-b05a4947-7865-4839-bbe0-18259b48b42e.png)

# SQL Commands 📌

- The standard SQL commands to interact with relational databases are CREATE, SELECT, INSERT, UPDATE, DELETE and DROP. 
- These commands can be classified into the following groups based on their nature −

![image](https://user-images.githubusercontent.com/43011442/127164103-88c322ea-a2c0-4c6e-a0ad-40a8426ee826.png)


## DDL - Data Definition Language 😀

### CREATE
- Creates a new table, a view of a table, or other object in the database.
	
### ALTER
- Modifies an existing database object, such as a table.

### DROP
- Deletes an entire table, a view of a table or other objects in the database.

## DML - Data Manipulation Language 😀

### INSERT
- Creates a record.

### UPDATE
= Modifies records.
	
### DELETE
- Deletes records.

# DCL - Data Control Language 😀

### GRANT
- Gives a privilege to user.

### REVOKE
- Takes back privileges granted from user.

# TCL - Transaction Control Language 😀

### COMMIT
- Save all the transactions to the database.

### ROLLBACK
- Undo transactions that have not already been saved to the database.

### SAVEPOINT
- Roll the transaction back to a certain point without rolling back the entire transaction.

## Data Query Language 😀

### SELECT
- select the attribute based on the condition described by WHERE clause.

# RDBMS ⌛

- RDBMS stands for Relational Database Management System. 
- RDBMS is the basis for SQL, and for all modern database systems like MS SQL Server, IBM DB2, Oracle, MySQL, and Microsoft Access.
- A Relational database management system (RDBMS) is a database management system (DBMS) that is based on the relational model as introduced by E. F. Codd.

## Tables 🎰

- The data in an RDBMS is stored in database objects which are called as tables. 
- This table is basically a collection of related data entries and it consists of numerous columns and rows.

## Field 🎯 

- Every table is broken up into smaller entities called fields. 
- The fields in the CUSTOMERS table consist of ID, NAME, AGE, ADDRESS and SALARY.
- A field is a column in a table that is designed to maintain specific information about every record in the table.

## Record 🎲

- A record is also called as a row of data is each individual entry that exists in a table.

## Column 🏹

- A column is a vertical entity in a table that contains all information associated with a specific field in a table.

## NULL value 🚫

- A NULL value in a table is a value in a field that appears to be blank, which means a field with a NULL value is a field with no value.
- It is very important to understand that a NULL value is different than a zero value or a field that contains spaces. 
- A field with a NULL value is the one that has been left blank during a record creation.

# SQL Constraints 🚩

- Constraints are the rules enforced on data columns on a table. 
- These are used to limit the type of data that can go into a table. 
- This ensures the accuracy and reliability of the data in the database.
- Constraints can either be column level or table level. 
- Column level constraints are applied only to one column whereas, table level constraints are applied to the entire table.

Following are some of the most commonly used constraints available in SQL −

### NOT NULL Constraint 
− Ensures that a column cannot have a NULL value.

### DEFAULT Constraint 
− Provides a default value for a column when none is specified.

### UNIQUE Constraint 
− Ensures that all the values in a column are different.

### PRIMARY Key 
− Uniquely identifies each row/record in a database table.

### FOREIGN Key 
− Uniquely identifies a row/record in any another database table.

### CHECK Constraint 
− The CHECK constraint ensures that all values in a column satisfy certain conditions.

### INDEX  
− Used to create and retrieve data from the database very quickly.

# Data Integrity 🚧

- The following categories of data integrity exist with each RDBMS −

**Entity Integrity − There are no duplicate rows in a table.**

**Domain Integrity − Enforces valid entries for a given column by restricting the type, the format, or the range of values.**

**Referential integrity − Rows cannot be deleted, which are used by other records.**

**User-Defined Integrity − Enforces some specific business rules that do not fall into entity, domain or referential integrity.**

# Database Normalization 🚀

- Database normalization is the process of efficiently organizing data in a database. 
- There are two reasons of this normalization process −

**1) Eliminating redundant data, for example, storing the same data in more than one table.**

**2) Ensuring data dependencies make sense.**

- Both these reasons are worthy goals as they reduce the amount of space a database consumes and ensures that data is logically stored. 
- Normalization consists of a series of guidelines that help guide you in creating a good database structure.
- Normalization guidelines are divided into normal forms; think of a form as the format or the way a database structure is laid out. 
- The aim of normal forms is to organize the database structure, so that it complies with the rules of first normal form, then second normal form and finally the third normal form.

- It is your choice to take it further and go to the fourth normal form, fifth normal form and so on, but in general, the third normal form is more than enough.

**First Normal Form (1NF)**
**Second Normal Form (2NF)**
**Third Normal Form (3NF)**
