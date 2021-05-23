# SQL
EVERYTHING I LEARNED ON SQL 

SQL (Structured Query Language)
SQL is a database computer language used in retrieving and modifying a data in a relational database management system.

Relational Database Management System (RDBMS)
The relational database management system serves as the link between different database tables, the database in an RDBMS is stored in a database object called TABLE
 
 DATABASE TABLE
The table is a collection of related database entries, and consist of rows and columns.

the field is a column that stores a particular set of related data
the record are stored in row, and they are information about a perticular subject

DATA CONSTRAINT 
These are rules that are used to limit data entries in a table, it can either be applied to a column or the entire table.
code example
(SELECT firstname, lastname and address
FROM contacts
)

types of operators
1. Aritmetic operator (+,-,*,% and /)
2. comparism operator (=,!=,<,>,<>,!<,!>,<=,>=,)
3. logical operator (and, in, between, any, and, all, like, not, unique, is not)
 logical operator (BETWEEN) code example 
 (SELECT * FROM Table1
 ORDER BY age
 BETWEEN 10 200)

EXPRESSION
An expression is a combinatin of one or more value, either an operator or a function that elevates to a value.
code example (WHERE)
(SELECT * FROM table1
ORDER BY firstname
WHERE country = nigeria)

BASIC DATABASE SYNTAX
1. create database ( CREATE DATABASE databaseName) to create 
2. DROP database ( DROP DATABASE databaseName) to delete 
3. USE database ( USE databaseName) to select from a list of database
4. CREATE TABLE example>>>> CREATE TABLE table_name( 
   column1 datatype,
   column2 datatype,
   column3 datatype,
   .....
   columnN datatype,
   PRIMARY KEY(one or more column));
5. DROP TABLE ()


