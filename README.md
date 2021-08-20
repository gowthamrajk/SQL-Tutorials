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
- The NOT operator reverses the meaning of the logical operator with which it is used. Eg: NOT EXISTS, NOT BETWEEN, NOT IN, etc. This is a negate operator.
### OR
- The OR operator is used to combine multiple conditions in an SQL statement's WHERE clause.
### IS NULL
- The NULL operator is used to compare a value with a NULL value.
### UNIQUE
- The UNIQUE operator searches every row of a specified table for uniqueness (no duplicates).

# SQL - Expressions ✍

- SQL EXPRESSIONs are like formulae and they are written in query language. You can also use them to query the database for a specific set of data.

      SELECT column1, column2, columnN 
      FROM table_name 
      WHERE [CONDITION|EXPRESSION];
      
- There are different types of SQL expressions, which are mentioned below −

**1) Boolean**

**2) Numeric**

**3) Date**

## Boolean Expressions

    SELECT column1, column2, columnN 
    FROM table_name 
    WHERE SINGLE VALUE MATCHING EXPRESSION;
    
## Numeric Expression

    SELECT numerical_expression as  OPERATION_NAME
    [FROM table_name
    WHERE CONDITION] ;
    
## Date Expressions

    SELECT CURRENT_TIMESTAMP;

    SELECT  GETDATE();
    
# SQL - Using Joins ⭕

- The SQL Joins clause is used to combine records from two or more tables in a database. 
- A JOIN is a means for combining fields from two tables by using values common to each.
- It is noticeable that the join is performed in the WHERE clause. 
- Several operators can be used to join tables, such as =, <, >, <>, <=, >=, !=, BETWEEN, LIKE, and NOT; they can all be used to join tables. 
- However, the most common operator is the equal to symbol.

There are different types of joins available in SQL −

**1) INNER JOIN − returns rows when there is a match in both tables.**

**2) LEFT JOIN − returns all rows from the left table, even if there are no matches in the right table.**

**3) RIGHT JOIN − returns all rows from the right table, even if there are no matches in the left table.**

**4) FULL JOIN − returns rows when there is a match in one of the tables.**

**5) SELF JOIN − is used to join a table to itself as if the table were two tables, temporarily renaming at least one table in the SQL statement.**

**6) CARTESIAN JOIN − returns the Cartesian product of the sets of records from the two or more joined tables.**

# Various Syntax for Joins 🚨

## 1) INNER JOIN

    SELECT table1.column1,table1.column2,table2.column1,....
    FROM table1 
    INNER JOIN table2
    ON table1.matching_column = table2.matching_column;


    table1: First table.
    table2: Second table
    matching_column: Column common to both the tables.
    
## 2) LEFT JOIN

    SELECT table1.column1,table1.column2,table2.column1,....
    FROM table1 
    LEFT JOIN table2
    ON table1.matching_column = table2.matching_column;


    table1: First table.
    table2: Second table
    matching_column: Column common to both the tables.
    
## 3) RIGHT JOIN

    SELECT table1.column1,table1.column2,table2.column1,....
    FROM table1 
    RIGHT JOIN table2
    ON table1.matching_column = table2.matching_column;


    table1: First table.
    table2: Second table
    matching_column: Column common to both the tables.
    
## 4) FULL JOIN

    SELECT table1.column1,table1.column2,table2.column1,....
    FROM table1 
    FULL JOIN table2
    ON table1.matching_column = table2.matching_column;


    table1: First table.
    table2: Second table
    matching_column: Column common to both the tables.
    
## 5) SELF JOIN

    SELECT a.coulmn1 , b.column2
    FROM table_name a, table_name b
    WHERE some_condition;

    table_name: Name of the table.
    some_condition: Condition for selecting the rows.

## 6) CARTESIAN JOIN

    SELECT table1.column1 , table1.column2, table2.column1...
    FROM table1
    CROSS JOIN table2;


    table1: First table.
    table2: Second table
    
# SQL - UNIONS CLAUSE ✅

- The SQL UNION clause/operator is used to combine the results of two or more SELECT statements without returning any duplicate rows.
- To use this UNION clause, each SELECT statement must have

**- The same number of columns selected**

**- The same number of column expressions**

**- The same data type and have them in the same order**

## UNION

    SELECT column1 [, column2 ]
    FROM table1 [, table2 ]
    [WHERE condition]
    UNION
    SELECT column1 [, column2 ]
    FROM table1 [, table2 ]
    [WHERE condition]
    
## UNION ALL

    SELECT column1 [, column2 ]
    FROM table1 [, table2 ]
    [WHERE condition]
    UNION ALL
    SELECT column1 [, column2 ]
    FROM table1 [, table2 ]
    [WHERE condition]

## INTERSECT

    SELECT column1 [, column2 ]
    FROM table1 [, table2 ]
    [WHERE condition]
    INTERSECT
    SELECT column1 [, column2 ]
    FROM table1 [, table2 ]
    [WHERE condition]
    
## EXCEPT

    SELECT column1 [, column2 ]
    FROM table1 [, table2 ]
    [WHERE condition]
    EXCEPT
    SELECT column1 [, column2 ]
    FROM table1 [, table2 ]
    [WHERE condition]

# SQL - NULL Values ⛔

- SQL NULL is the term used to represent a missing value. 
- A NULL value in a table is a value in a field that appears to be blank.
- A field with a NULL value is a field with no value. 
- It is very important to understand that a NULL value is different than a zero value or a field that contains spaces.

      CREATE TABLE CUSTOMERS(
          ID   INT              NOT NULL,
          NAME VARCHAR (20)     NOT NULL,
          AGE  INT              NOT NULL,
          ADDRESS  CHAR (25) ,
          SALARY   DECIMAL (18, 2),       
          PRIMARY KEY (ID)
      );

# SQL - Alias ✍

- The use of table aliases is to rename a table in a specific SQL statement. 
- The renaming is a temporary change and the actual table name does not change in the database. 
- The column aliases are used to rename a table's columns for the purpose of a particular SQL query.

      SELECT column1, column2....
      FROM table_name AS alias_name
      WHERE [condition];
      
# SQL - Indexes ✌

- Indexes are special lookup tables that the database search engine can use to speed up data retrieval. 
- Simply put, an index is a pointer to data in a table. 
- An index in a database is very similar to an index in the back of a book.

The following guidelines indicate when the use of an index should be reconsidered.

**- Indexes should not be used on small tables.**

**- Tables that have frequent, large batch updates or insert operations.**

**- Indexes should not be used on columns that contain a high number of NULL values.**

**- Columns that are frequently manipulated should not be indexed.**

### CREATE INDEX

    CREATE INDEX index_name ON table_name;

### Single-Column Indexes
- A single-column index is created based on only one table column.

      CREATE INDEX index_name
      ON table_name (column_name);
      
### Unique Indexes
- Unique indexes are used not only for performance, but also for data integrity. 
- A unique index does not allow any duplicate values to be inserted into the table.

      CREATE UNIQUE INDEX index_name
      on table_name (column_name);

### Composite Indexes
- A composite index is an index on two or more columns of a table.

      CREATE INDEX index_name
      on table_name (column1, column2);
      
### Implicit Indexes
- Implicit indexes are indexes that are automatically created by the database server when an object is created. 
- Indexes are automatically created for primary key constraints and unique constraints.

### DROP INDEX

    DROP INDEX index_name;

# SQL - ALTER TABLE  ✍

- The SQL ALTER TABLE command is used to add, delete or modify columns in an existing table. 
- You should also use the ALTER TABLE command to add and drop various constraints on an existing table.

### New Column
 
    ALTER TABLE table_name ADD column_name datatype;

### DROP COLUMN

    ALTER TABLE table_name DROP COLUMN column_name;
    
### Change DATA TYPE

    ALTER TABLE table_name MODIFY COLUMN column_name datatype;

### NOT NULL

    ALTER TABLE table_name MODIFY column_name datatype NOT NULL;
    
### ADD UNIQUE CONSTRAINT

    ALTER TABLE table_name 
    ADD CONSTRAINT MyUniqueConstraint UNIQUE(column1, column2...);
    
### ADD CHECK CONSTRAINT

    ALTER TABLE table_name 
    ADD CONSTRAINT MyUniqueConstraint CHECK (CONDITION);

### ADD PRIMARY KEY

    ALTER TABLE table_name 
    ADD CONSTRAINT MyPrimaryKey PRIMARY KEY (column1, column2...);
    
### DROP CONSTRAINT

    ALTER TABLE table_name 
    DROP CONSTRAINT MyUniqueConstraint;
    
    ALTER TABLE table_name 
    DROP INDEX MyUniqueConstraint;

### DROP PRIMARY KEY

    ALTER TABLE table_name 
    DROP CONSTRAINT MyPrimaryKey;
    
    ALTER TABLE table_name 
    DROP PRIMARY KEY;
    
# SQL - TRUNCATE TABLE 🎲

- The SQL TRUNCATE TABLE command is used to delete complete data from an existing table.
- You can also use DROP TABLE command to delete complete table but it would remove complete table structure form the database and you would need to re-create this table once again if you wish you store some data.

      TRUNCATE TABLE  table_name;

# SQL - Using Views ⭐

- A view is nothing more than a SQL statement that is stored in the database with an associated name. 
- A view is actually a composition of a table in the form of a predefined SQL query.
- A view can contain all rows of a table or select rows from a table. 
- A view can be created from one or many tables which depends on the written SQL query to create a view.
- 
Views, which are a type of virtual tables allow users to do the following −

**- Structure data in a way that users or classes of users find natural or intuitive.**

**- Restrict access to the data in such a way that a user can see and (sometimes) modify exactly what they need and no more.**

**- Summarize data from various tables which can be used to generate reports.**

## Creating Views

    CREATE VIEW view_name AS
    SELECT column1, column2.....
    FROM table_name
    WHERE [condition];
    
## WITH CHECK OPTION

- The WITH CHECK OPTION is a CREATE VIEW statement option. 
- The purpose of the WITH CHECK OPTION is to ensure that all UPDATE and INSERTs satisfy the condition(s) in the view definition.
- If they do not satisfy the condition(s), the UPDATE or INSERT returns an error.

      CREATE VIEW CUSTOMERS_VIEW AS
      SELECT name, age
      FROM  CUSTOMERS
      WHERE age IS NOT NULL
      WITH CHECK OPTION;  
      
## Updating a View

A view can be updated under certain conditions which are given below −

**- The SELECT clause may not contain the keyword DISTINCT.**

**- The SELECT clause may not contain summary functions.**

**- The SELECT clause may not contain set functions.**

**- The SELECT clause may not contain set operators.**

**- The SELECT clause may not contain an ORDER BY clause.**

**- The FROM clause may not contain multiple tables.**

**- The WHERE clause may not contain subqueries.**

**- The query may not contain GROUP BY or HAVING.**

**- Calculated columns may not be updated.**

**- All NOT NULL columns from the base table must be included in the view in order for the INSERT query to function.**

## Inserting Rows into a View

- Rows of data can be inserted into a view. 
- The same rules that apply to the UPDATE command also apply to the INSERT command.

## Deleting Rows into a View

- Rows of data can be deleted from a view. 
- The same rules that apply to the UPDATE and INSERT commands apply to the DELETE command.

## Dropping Views

    DROP VIEW view_name;
    
# SQL - Having Clause 🚨

- The HAVING Clause enables you to specify conditions that filter which group results appear in the results.
- The WHERE clause places conditions on the selected columns, whereas the HAVING clause places conditions on groups created by the GROUP BY clause.

      SELECT column1, column2
      FROM table1, table2
      WHERE [ conditions ]
      GROUP BY column1, column2
      HAVING [ conditions ]
      ORDER BY column1, column2
      
# SQL - Transactions ⭐

- A transaction is a unit of work that is performed against a database. 
- Transactions are units or sequences of work accomplished in a logical order, whether in a manual fashion by a user or automatically by some sort of a database program.
- A transaction is the propagation of one or more changes to the database. 
- For example, if you are creating a record or updating a record or deleting a record from the table, then you are performing a transaction on that table. 
- It is important to control these transactions to ensure the data integrity and to handle database errors.

## Properties of Transactions

Transactions have the following four standard properties, usually referred to by the acronym ACID.

**Atomicity** - ensures that all operations within the work unit are completed successfully.Otherwise, the transaction is aborted at the point of failure and all the previous operations are rolled back to their former state.

**Consistency** − ensures that the database properly changes states upon a successfully committed transaction.

**Isolation** − enables transactions to operate independently of and transparent to each other.

**Durability** − ensures that the result or effect of a committed transaction persists in case of a system failure.

## Transaction Control Commands

### COMMIT − to save the changes.

    COMMIT;

### ROLLBACK − to roll back the changes.

    ROLLBACK;

### SAVEPOINT − creates points within the groups of transactions in which to ROLLBACK.

    SAVEPOINT SAVEPOINT_NAME;
    
    ROLLBACK TO SAVEPOINT_NAME;
    
    RELEASE SAVEPOINT SAVEPOINT_NAME;

### SET TRANSACTION − Places a name on a transaction.

    SET TRANSACTION [ READ WRITE | READ ONLY ];

# SQL - Wildcard Operators ✅

### 1) The percent sign (%)

- Matches one or more characters.

**Note − MS Access uses the asterisk (*) wildcard character instead of the percent sign (%) wildcard character.**
	
### 2) The underscore (_)

- Matches one character.

**Note − MS Access uses a question mark (?) instead of the underscore (_) to match any one character.**

## Syntax

    SELECT * FROM table_name
    WHERE column LIKE 'XXXX%'
        
    (or)
    
    SELECT * FROM table_name
    WHERE column LIKE '%XXXX%'
    
    (or)
    
    SELECT * FROM table_name
    WHERE column LIKE 'XXXX_'
    
    (or)
    
    SELECT * FROM table_name
    WHERE column LIKE '_XXXX'
    
    (or)
    
    SELECT * FROM table_name
    WHERE column LIKE '_XXXX_'

### WHERE SALARY LIKE '200%'

- Finds any values that start with 200.

### WHERE SALARY LIKE '%200%'

- Finds any values that have 200 in any position.
	
### WHERE SALARY LIKE '_00%'

- Finds any values that have 00 in the second and third positions.

### WHERE SALARY LIKE '2_%_%'

- Finds any values that start with 2 and are at least 3 characters in length.

### WHERE SALARY LIKE '%2'

- Finds any values that end with 2.

### WHERE SALARY LIKE '_2%3'

- Finds any values that have a 2 in the second position and end with a 3.
	
### WHERE SALARY LIKE '2___3'

- Finds any values in a five-digit number that start with 2 and end with 3.

# SQL - Date Functions 📅

### ADDDATE() - Adds dates

### ADDTIME() - Adds time

### CONVERT_TZ() - Converts from one timezone to another

### CURDATE() - Returns the current date

### CURRENT_DATE(), CURRENT_DATE - Synonyms for CURDATE()

### CURRENT_TIME(), CURRENT_TIME - Synonyms for CURTIME()

### CURRENT_TIMESTAMP(), CURRENT_TIMESTAMP - Synonyms for NOW()

### CURTIME() - Returns the current time

### ATE_ADD() - Adds two dates

### DATE_FORMAT() - Formats date as specified

### DATE_SUB() - Subtracts two dates

### DATE() - Extracts the date part of a date or datetime expression

### DATEDIFF() - Subtracts two dates

### DAY() - Synonym for DAYOFMONTH()

### DAYNAME() - Returns the name of the weekday

### DAYOFMONTH() - Returns the day of the month (1-31)

### DAYOFWEEK() - Returns the weekday index of the argument

### DAYOFYEAR() - Returns the day of the year (1-366)

### EXTRACT - Extracts part of a date

### FROM_DAYS() - Converts a day number to a date

### FROM_UNIXTIME() - Formats date as a UNIX timestamp

### HOUR() - Extracts the hour

### LAST_DAY - Returns the last day of the month for the argument

### LOCALTIME(), LOCALTIME - Synonym for NOW()

### LOCALTIMESTAMP, LOCALTIMESTAMP() - Synonym for NOW()

### MAKEDATE() - Creates a date from the year and day of year

### MAKETIME - MAKETIME()

### MICROSECOND() - Returns the microseconds from argument

### MINUTE() - Returns the minute from the argument

### MONTH() - Return the month from the date passed

### MONTHNAME() - Returns the name of the month

### NOW() - Returns the current date and time

### PERIOD_ADD() - Adds a period to a year-month

### PERIOD_DIFF() - Returns the number of months between periods

### QUARTER() - Returns the quarter from a date argument

### SEC_TO_TIME() - Converts seconds to 'HH:MM:SS' format

### SECOND() - Returns the second (0-59)

### STR_TO_DATE() - Converts a string to a date

### SUBDATE() - When invoked with three arguments a synonym for DATE_SUB()

### SUBTIME() - Subtracts times

### SYSDATE() - Returns the time at which the function executes

### TIME_FORMAT() - Formats as time

### TIME_TO_SEC() - Returns the argument converted to seconds

### TIME() - Extracts the time portion of the expression passed

### TIMEDIFF() - Subtracts time

### TIMESTAMP() - With a single argument this function returns the date or datetime expression. With two arguments, the sum of the arguments

### TIMESTAMPADD() - Adds an interval to a datetime expression

### IMESTAMPDIFF() - Subtracts an interval from a datetime expression

### TO_DAYS() - Returns the date argument converted to days

### UNIX_TIMESTAMP() - Returns a UNIX timestamp

### UTC_DATE() - Returns the current UTC date

### UTC_TIME() - Returns the current UTC time

### UTC_TIMESTAMP() - Returns the current UTC date and time

### WEEK() - Returns the week number

### WEEKDAY() - Returns the weekday index

### WEEKOFYEAR() - Returns the calendar week of the date (1-53)

### YEAR() - Returns the year

### YEARWEEK() - Returns the year and week
