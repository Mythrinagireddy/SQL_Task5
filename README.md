# Task 5 – SQL Joins

## Objective
To learn and demonstrate how to combine data from multiple tables using various SQL JOINs.

## Tables Used
- **Customers** – Contains customer information
- **Orders** – Contains orders placed by customers

## Joins Used

1. **INNER JOIN**
   - Returns only records with matching values in both tables.
2. **LEFT JOIN**
   - Returns all records from the left table (Customers) and matched records from the right table (Orders).
3. **RIGHT JOIN**
   - Returns all records from the right table (Orders) and matched records from the left table (Customers).
4. **FULL OUTER JOIN**
   - Combines results of both LEFT and RIGHT joins, showing all records with NULL where there’s no match.

## How to Run
- Use MySQL Workbench or DB Browser for SQLite
- Copy and run `task5.sql` to create tables and execute join queries
- Check the output for how data is merged using different JOINs

## Output Screenshots
Screenshots of SQL join outputs are included in the repo.