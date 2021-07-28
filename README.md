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

**1) High Performance**

**2) High Availability**

**3) Database mirroring**

**4) Database snapshots**

**5) CLR integration**

**6) Service Broker**

**7) DDL triggers**

**8) Ranking functions**

**9) Row version-based isolation levels**

**10) XML integration**

**11) TRY...CATCH**

**12) Database Mail**

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

### !) NOT NULL Constraint 
− Ensures that a column cannot have a NULL value.

### 2) DEFAULT Constraint 
− Provides a default value for a column when none is specified.

### 3) UNIQUE Constraint 
− Ensures that all the values in a column are different.

### 4) PRIMARY Key 
− Uniquely identifies each row/record in a database table.

### 5) FOREIGN Key 
− Uniquely identifies a row/record in any another database table.

### 6) CHECK Constraint 
− The CHECK constraint ensures that all values in a column satisfy certain conditions.

### 7) INDEX  
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

# Various Syntax in SQL 🚨

### SQL SELECT Statement
    SELECT column1, column2....columnN
    FROM   table_name;
 
### SQL DISTINCT Clause
    SELECT DISTINCT column1, column2....columnN
    FROM   table_name;

### SQL WHERE Clause
    SELECT column1, column2....columnN
    FROM   table_name
    WHERE  CONDITION;
    
### SQL AND/OR Clause
    SELECT column1, column2....columnN
    FROM   table_name
    WHERE  CONDITION-1 {AND|OR} CONDITION-2;
    
### SQL IN Clause
    SELECT column1, column2....columnN
    FROM   table_name
    WHERE  column_name IN (val-1, val-2,...val-N);

### SQL BETWEEN Clause
    SELECT column1, column2....columnN
    FROM   table_name
    WHERE  column_name BETWEEN val-1 AND val-2;
    
### SQL LIKE Clause
    SELECT column1, column2....columnN
    FROM   table_name
    WHERE  column_name LIKE { PATTERN };
    
### SQL ORDER BY Clause
    SELECT column1, column2....columnN
    FROM   table_name
    WHERE  CONDITION
    ORDER BY column_name {ASC|DESC};
    
### SQL GROUP BY Clause
    SELECT SUM(column_name)
    FROM   table_name
    WHERE  CONDITION
    GROUP BY column_name;

### SQL COUNT Clause
    SELECT COUNT(column_name)
    FROM   table_name
    WHERE  CONDITION;
    
### SQL HAVING Clause
    SELECT SUM(column_name)
    FROM   table_name
    WHERE  CONDITION
    GROUP BY column_name
    HAVING (arithematic function condition);
    
### SQL CREATE TABLE Statement
    CREATE TABLE table_name(
        column1 datatype,
        column2 datatype,
        column3 datatype,
        .....
        columnN datatype,
        PRIMARY KEY( one or more columns )
    );
    
### SQL DROP TABLE Statement
    DROP TABLE table_name;

### SQL CREATE INDEX Statement
    CREATE UNIQUE INDEX index_name
    ON table_name ( column1, column2,...columnN);
    
### SQL DROP INDEX Statement
    ALTER TABLE table_name
    DROP INDEX index_name;
    
### SQL DESC Statement
    DESC table_name;
    
### SQL TRUNCATE TABLE Statement
    TRUNCATE TABLE table_name;
    
### SQL ALTER TABLE Statement
    ALTER TABLE table_name {ADD|DROP|MODIFY} column_name {data_ype};
    
### SQL ALTER TABLE Statement (Rename)
    ALTER TABLE table_name RENAME TO new_table_name;
    
### SQL INSERT INTO Statement
    INSERT INTO table_name( column1, column2....columnN)
    VALUES ( value1, value2....valueN);
    
### SQL UPDATE Statement
    UPDATE table_name
    SET column1 = value1, column2 = value2....columnN=valueN
    [ WHERE  CONDITION ];
    
### SQL DELETE Statement
    DELETE FROM table_name
    WHERE  {CONDITION};
    
### SQL CREATE DATABASE Statement
    CREATE DATABASE database_name;
    
### SQL DROP DATABASE Statement
    DROP DATABASE database_name;
    
### SQL USE Statement
    USE database_name;
    
### SQL COMMIT Statement
    COMMIT;
    
### SQL ROLLBACK Statement
    ROLLBACK;

# SQL - Data Types 🧐

- SQL Data Type is an attribute that specifies the type of data of any object. 
- Each column, variable and expression has a related data type in SQL. 
- You can use these data types while creating your tables. 
- You can choose a data type for a table column based on your requirement.
- SQL Server offers six categories of data types for your use which are listed below −

## 1) Exact Numeric Data Types  

![image](https://user-images.githubusercontent.com/43011442/127181387-5c8a3c74-b852-4de7-a3f9-12903a6be7c9.png)

## 2) Approximate Numeric Data Types

![image](https://user-images.githubusercontent.com/43011442/127271215-c79c162d-b983-4e70-902b-a43929e805a6.png)

## 3) Date and Time Data Types

![image](https://user-images.githubusercontent.com/43011442/127271285-779bde09-bd62-4d0f-8045-4665634b6fea.png)

## 4) Character Strings Data Types

![image](https://user-images.githubusercontent.com/43011442/127271776-4527e3c4-4678-4ec5-af5b-da91ad8fb2c2.png)

## 5) Unicode Character Strings Data Types

![image](https://user-images.githubusercontent.com/43011442/127271707-44cf339e-fb15-4159-b992-926415df6031.png)

## 6) Binary Data Types

![image](https://user-images.githubusercontent.com/43011442/127271659-85b26188-5043-4a31-a537-a5be85882ebd.png)

## 7) Misc Data Types

![image](https://user-images.githubusercontent.com/43011442/127271918-8bf12f0f-d137-4373-bb2a-2c46436c06c7.png)

# Operator in SQL ⚡

- An operator is a reserved word or a character used primarily in an SQL statement's WHERE clause to perform operation(s), such as comparisons and arithmetic operations.
- These Operators are used to specify conditions in an SQL statement and to serve as conjunctions for multiple conditions in a statement.

**- Arithmetic operators**

**- Comparison operators**

**- Logical operators**

**- Operators used to negate conditions**

## SQL Arithmetic Operators ✨

### + (Addition)
- Adds values on either side of the operator.
### - (Subtraction)
- Subtracts right hand operand from left hand operand.
### * (Multiplication)
- Multiplies values on either side of the operator.
### / (Division)
- Divides left hand operand by right hand operand.
### % (Modulus)
- Divides left hand operand by right hand operand and returns remainder.

## SQL Comparison Operators ⭐

### = (Equals)
- Checks if the values of two operands are equal or not, if yes then condition becomes true.
### != (NotEquals)
- Checks if the values of two operands are equal or not, if values are not equal then condition becomes true.
### <> (Equality)
- Checks if the values of two operands are equal or not, if values are not equal then condition becomes true.
### > (Greater than)
- Checks if the value of left operand is greater than the value of right operand, if yes then condition becomes true.
### < (Lesser than)
- Checks if the value of left operand is less than the value of right operand, if yes then condition becomes true.
### >= (Greater than or Equal to)
- Checks if the value of left operand is greater than or equal to the value of right operand, if yes then condition becomes true.
### <= (Lesser than or Equal to)
- Checks if the value of left operand is less than or equal to the value of right operand, if yes then condition becomes true.
### !< (Not Less than)
- Checks if the value of left operand is not less than the value of right operand, if yes then condition becomes true.
### !> (Not Greater than)
- Checks if the value of left operand is not greater than the value of right operand, if yes then condition becomes true.

## SQL Logical Operators ❗

### ALL
- The ALL operator is used to compare a value to all values in another value set.	
### AND
- The AND operator allows the existence of multiple conditions in an SQL statement's WHERE clause.
### ANY
- The ANY operator is used to compare a value to any applicable value in the list as per the condition.
### BETWEEN
- The BETWEEN operator is used to search for values that are within a set of values, given the minimum value and the maximum value.
### EXISTS
- The EXISTS operator is used to search for the presence of a row in a specified table that meets a certain criterion.
### IN
- The IN operator is used to compare a value to a list of literal values that have been specified.
### LIKE
- The LIKE operator is used to compare a value to similar values using wildcard operators.
### NOT

The NOT operator reverses the meaning of the logical operator with which it is used. Eg: NOT EXISTS, NOT BETWEEN, NOT IN, etc. This is a negate operator.

9	
OR

The OR operator is used to combine multiple conditions in an SQL statement's WHERE clause.

10	
IS NULL

The NULL operator is used to compare a value with a NULL value.

11	
UNIQUE

The UNIQUE operator searches every row of a specified table for uniqueness (no duplicates).
