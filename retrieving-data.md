# Retrieving Data with SQL

## SELECT Statment

Used to retrieve data from a database
`SELECT column1, column2 FROM table`

**Example**
`SELECT FirstName, LastName FROM Customers;`

## WHERE Clause

Used to filter a result set
`SELECT column1, column2 FROM table WHERE condition`

**Example**
`SELECT FirstName, LastName FROM Customers WHERE LastName = 'Smith'`

## HAVING Clause

Used to filter a result set for aggregate functions (COUNT, SUM, MIN, AVG, etc.) where a WHERE clause can't be used
`SELECT column_name(s) FROM table WHERE condition HAVING condition`

**Example**
`SELECT COUNT(CustomerID) FROM Customers HAVING COUNT(CustomerID) > 5;`

## SORTING

Used to order a result set by ascending or descending
`SELECT column1, column2 FROM table ORDER BY column1 ASC|DESC`

**Example**
`SELECT FirstName, LastName FROM Customers ORDER BY State DESC`
