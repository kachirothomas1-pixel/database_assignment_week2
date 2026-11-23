# Week 2 Assignment: Introduction to SQL

This repository contains my SQL solutions for the Week 2 Introduction to SQL assignment. The queries use the `sales` database.

## Topics covered

- Selecting specific columns with `SELECT`
- Filtering rows with `WHERE`
- Sorting results with `ORDER BY`
- Limiting results with `LIMIT`
- Retrieving all columns with `SELECT *`

## Database setup

1. Import the provided `sales` database into your MySQL server.
2. Confirm that it is available:

   ```sql
   SHOW DATABASES;
   ```

3. Select the database:

   ```sql
   USE sales;
   ```

4. Open and run [assignment.sql](assignment.sql) in your SQL client.

> The database itself is not included in this repository. Import the course-provided database before running the queries.

## Assignment solutions

### Question 1: Retrieve payment information

Selects the check number, payment date, and amount from the `payments` table.

### Question 2: Find orders in process

Filters the `orders` table to records with status `In Process` and sorts by `orderDate` from newest to oldest.

### Question 3: Find sales representatives

Filters employees to the `Sales Rep` job title and sorts by `employeeNumber` in descending order. The employee number is used for sorting but is not included in the requested output columns.

### Question 4: Retrieve office information

Returns all columns and rows from the `offices` table.

### Question 5: Retrieve the five cheapest products

Sorts products by `buyPrice` from lowest to highest and returns the first five rows, displaying the product name and quantity in stock.

## Files

- `assignment.sql` — all five SQL queries, ready to run.
- `README.md` — setup instructions and a summary of the solutions.
