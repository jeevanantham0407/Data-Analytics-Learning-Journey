
---

# 2. `Reading-SQL-Data-into-Pandas/README.md`

```markdown
# Reading SQL Data into Pandas

## Overview

This section covers how to retrieve data from a MySQL database and load it directly into a Pandas DataFrame.

The `pandas` library was used to execute SQL queries and convert the returned data into a DataFrame for further analysis.

## Technologies Used

- Python
- MySQL
- Pandas
- mysql-connector-python
- VS Code
- MySQL Workbench

## Topics Covered

### 1. Connecting Python to MySQL

Established a connection between Python and the MySQL database.

### 2. Executing SQL Queries

Used SQL queries to retrieve required data from the database.

Examples of queries practiced:

- SELECT
- WHERE
- ORDER BY
- SUM
- AVG
- COUNT
- MAX
- MIN
- GROUP BY

### 3. Reading SQL Data into Pandas

Used `pd.read_sql()` to load SQL query results into a Pandas DataFrame.

```python
df = pd.read_sql(query, connection)