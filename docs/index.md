# SQL Functions

## Introduction
**SQL functions** are simply sub-programs, which are commonly used and re-used throughout SQL database applications for processing or manipulating data. Basically, it is a **set of SQL statements that accept only input parameters, perform actions and return the result**. The function can return only a single value or a table. We can't use a function to Insert, Update, Delete records in the database table(s).

## SQL Function
While a view is nothing more than a SQL statement that is stored in the database with an associated name. A function on the other hand returns a single value or a single result set after accepting input parameters.
Functions **foster code reusability**. If there is need to repeatedly write large SQL scripts to perform the same task, then we can create a function that performs that task. Next time instead of rewriting the SQL, specific function can be called.
The basic CREATE FUNCTION syntax is as follows –

<img src="./Images/Figure1.png"/>
##### Fig1: Basic syntax of SQL function 

### View And Functions
In addition to SQL Server's built-in functions, you can create custom functions. These are often called User Defined Functions or just UDFs. There are two basic types of functions; functions that return a table of values and functions that return a single value.
•	Functions and Views are similar as both can return a table of values.
•	Unlike views, functions can use parameters to change the results of the query
•	Unlike views, you can create UDFs to return a single (scalar) value as an expression.
