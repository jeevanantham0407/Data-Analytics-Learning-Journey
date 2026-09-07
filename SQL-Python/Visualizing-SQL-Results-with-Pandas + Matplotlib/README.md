
---

# 3. `Visualizing-SQL-Results-with-Pandas-Matplotlib/README.md`

```markdown
# Visualizing SQL Results with Pandas and Matplotlib

## Overview

This section covers the process of retrieving analytical results from MySQL, loading them into Pandas, and creating visualizations using Matplotlib.

The workflow combines SQL for data analysis, Pandas for data handling, and Matplotlib for visual presentation.

## Technologies Used

- Python
- MySQL
- Pandas
- Matplotlib
- mysql-connector-python
- VS Code
- MySQL Workbench

## Topics Covered

### 1. SQL Data Extraction

Retrieved required data from the MySQL database using SQL queries.

### 2. SQL Aggregation

Used SQL aggregation and grouping to prepare data for visualization.

Examples:

- Sales by Category
- Sales by Region
- Sales by Product
- Sales by Salesperson
- Monthly Sales
- Quantity Sold by Product

### 3. Loading Results into Pandas

Converted SQL query results into Pandas DataFrames using:

```python
df = pd.read_sql(query, connection)