# Pandas – Data Analysis with Python

## Overview

This repository contains my learning and practice work with Pandas as part of my Data Analytics learning journey.

Pandas is a Python library used for data manipulation and analysis. It provides powerful data structures such as Series and DataFrame for working with structured and tabular data.

In this module, I learned how to create and work with Series and DataFrames, read CSV files, inspect datasets, select and filter data, sort values, perform statistical analysis, group data, and extract useful insights.

The module also includes a Sample Dataset Analysis and a Sales Data Analysis mini project.

---

## Objectives

The main objectives of this module were:

- Understand the fundamentals of Pandas.
- Learn how to create and use Series.
- Learn how to create and work with DataFrames.
- Read CSV files using Pandas.
- Inspect and understand datasets.
- Select rows and columns.
- Filter data using conditions.
- Sort data.
- Perform basic statistical analysis.
- Count values in categorical columns.
- Group and aggregate data.
- Identify maximum and minimum values.
- Analyze a sample dataset.
- Apply Pandas concepts to a sales dataset.
- Extract meaningful business insights from data.

---

## Tools and Technologies

- Python
- Pandas
- CSV
- Jupyter Notebook
- VS Code
- Git
- GitHub

---

# Pandas Topics Covered

## 1. Series

Learned about Pandas Series, which is a one-dimensional labeled data structure.

Topics covered:

- Creating Series
- Accessing Series values
- Series indexing
- Working with Series
- Series data types
- Basic Series operations

---

## 2. DataFrame

Learned about DataFrames, which are two-dimensional tabular data structures containing rows and columns.

Topics covered:

- Creating DataFrames
- Creating DataFrames using dictionaries
- Working with rows and columns
- Accessing columns
- Accessing rows
- Checking DataFrame shape
- Checking column names
- Checking data types

---

## 3. Reading CSV Files

Learned how to load external datasets into Pandas using CSV files.

Topics covered:

- Reading CSV files
- Loading datasets
- Displaying datasets
- Working with external data
- Understanding the structure of a dataset

---

## 4. Dataset Inspection

Learned how to inspect a dataset before performing analysis.

Topics covered:

- Viewing the first records
- Viewing the last records
- Finding the number of rows and columns
- Checking column names
- Checking data types
- Checking missing values

Functions practiced:

- `head()`
- `tail()`
- `shape`
- `columns`
- `dtypes`
- `isnull()`
- `sum()`

---

## 5. Selecting Rows and Columns

Learned different methods for selecting specific data from a DataFrame.

Topics covered:

- Selecting a single column
- Selecting multiple columns
- Selecting rows
- Selecting specific rows and columns
- Label-based selection using `loc`
- Position-based selection using `iloc`

---

## 6. Filtering Data

Learned how to filter datasets based on conditions.

Topics covered:

- Greater than conditions
- Less than conditions
- Equal to conditions
- Not equal conditions
- Multiple conditions
- AND condition
- OR condition
- `isin()`
- `between()`

Filtering helps identify only the records that satisfy specific business or analytical requirements.

---

## 7. Sorting Data

Learned how to arrange data in ascending and descending order.

Topics covered:

- Sorting in ascending order
- Sorting in descending order
- Sorting using multiple columns
- Sorting numerical values
- Sorting categorical values
- Resetting indexes after sorting

Main function practiced:

- `sort_values()`

---

## 8. Statistical Analysis

Learned how to perform basic statistical calculations on numerical data.

Topics covered:

- Average
- Total
- Maximum value
- Minimum value
- Basic dataset statistics

Functions practiced:

- `mean()`
- `sum()`
- `max()`
- `min()`

---

## 9. Counting Values

Learned how to count the occurrence of unique values in a column.

Main function practiced:

- `value_counts()`

This can be used to answer questions such as:

- How many students belong to each department?
- How many sales were made for each product?
- How many records belong to each category?

---

## 10. GroupBy

Learned how to divide data into groups and perform calculations on each group.

Topics covered:

- Grouping data by a column
- Calculating totals for each group
- Calculating averages for each group
- Sorting grouped results
- Comparing groups

The `groupby()` operation is an important concept for Data Analysis because it allows large datasets to be summarized based on categories such as department, product, region, or salesperson.

---

## 11. Finding Maximum and Minimum Records

Learned how to identify records associated with the highest and lowest values.

Topics covered:

- Finding maximum values
- Finding minimum values
- Finding the record with the highest value
- Finding the record with the lowest value
- Using index-based identification

Functions practiced:

- `max()`
- `min()`
- `idxmax()`
- `idxmin()`

---

# Practice Programs

During this module, I created and practiced multiple Pandas programs covering:

1. Creating Pandas Series
2. Creating DataFrames
3. Reading CSV datasets
4. Inspecting datasets
5. Selecting rows and columns
6. Filtering data
7. Sorting data
8. Handling and checking missing values
9. Performing statistical calculations
10. Analyzing grouped data

These programs helped me understand the fundamentals of Pandas before applying them to datasets.

---

# Sample Dataset Analysis

## Student Data Analysis

I analyzed a sample student dataset using Pandas to practice data analysis operations.

The dataset contained information about students such as:

- Student ID
- Name
- Age
- Marks
- Department

### Analysis Performed

- Inspected the dataset structure
- Checked the number of rows and columns
- Checked column names
- Checked data types
- Checked missing values
- Calculated average age
- Calculated average marks
- Found the highest marks
- Found the lowest marks
- Identified high-scoring students
- Counted students by department
- Calculated average marks by department
- Identified top-performing students
- Compared department performance

This analysis helped me understand how Pandas can be used to analyze structured datasets.

---

# Mini Project – Sales Data Analysis

## Project Overview

The Sales Data Analysis mini project applies Pandas concepts to a sales dataset.

The purpose of this project was to analyze sales transactions and identify important business information such as total revenue, product performance, regional performance, category performance, and salesperson performance.

---

## Dataset Description

The sales dataset contains information about sales transactions.

The main columns include:

- Order ID
- Date
- Product
- Category
- Region
- Salesperson
- Quantity
- Unit Price
- Revenue

The Revenue column was calculated using the quantity sold and unit price.

---

## Sales Analysis Performed

### Overall Sales Analysis

- Calculated total revenue
- Calculated total quantity sold
- Calculated average order revenue
- Identified the highest-value order

### Product Analysis

- Calculated revenue for each product
- Sorted products based on revenue
- Identified the best-performing product

### Region Analysis

- Calculated revenue for each region
- Compared regional performance
- Identified the best-performing region

### Category Analysis

- Calculated revenue for each category
- Compared category performance
- Identified the best-performing category

### Salesperson Analysis

- Calculated revenue generated by each salesperson
- Compared salesperson performance
- Identified the best-performing salesperson

---

# Business Insights

The Sales Data Analysis project helped identify:

- The overall revenue generated by the business
- The total number of products sold
- The average revenue generated per order
- The highest-value sales transaction
- The product generating the highest revenue
- The region generating the highest revenue
- The category generating the highest revenue
- The salesperson generating the highest revenue

The analysis demonstrates how raw sales data can be transformed into useful information for business decision-making.

---

# Skills Demonstrated

Through this Pandas module and mini project, I developed practical experience in:

- Python
- Pandas
- Series
- DataFrames
- CSV data handling
- Dataset inspection
- Data selection
- Row and column selection
- Data filtering
- Data sorting
- Statistical analysis
- Value counting
- GroupBy operations
- Data aggregation
- Calculated columns
- Business data analysis
- Extracting insights from datasets

---

# Project Structure

```text
Pandas/
│
├── 01_series.py
├── 02_dataframe.py
├── 03_read_csv.py
├── 04_select_rows_columns.py
├── 05_filter_data.py
├── 06_sort_values.py
├── 07_sample_dataset_analysis.py
│
├── datasets/
│   ├── students.csv
│   └── sales.csv
│
├── mini_project/
│   └── sales_analysis.py
│
└── README.md