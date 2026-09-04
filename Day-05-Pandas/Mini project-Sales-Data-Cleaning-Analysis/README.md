# Sales Data Cleaning and Analysis Using Python

## Project Overview

This project focuses on cleaning and analyzing a dirty sales dataset using Python and Pandas. The dataset contained missing values, duplicate records, inconsistent column names, and incorrect data types.

The data was cleaned and analyzed to identify important business insights such as the best-performing region, product, category, and salesperson.

## Objectives

* Handle missing values
* Identify and remove duplicate records
* Standardize column names
* Convert columns into appropriate data types
* Perform data analysis using GroupBy
* Create summary reports using Pivot Tables
* Identify important business insights

## Dataset Description

The dataset contains sales-related information including:

* Order ID
* Customer Name
* Age
* Product
* Category
* Region
* Sales
* Order Date
* Salesperson

## Data Cleaning Process

### 1. Missing Values

Missing numerical and categorical values were handled using appropriate methods such as:

* Mean
* Median
* Mode

### 2. Duplicate Values

Duplicate records were identified using:

`duplicated()`

Duplicate rows were removed using:

`drop_duplicates()`

### 3. Column Name Standardization

Column names were converted to a consistent format by:

* Converting names to lowercase
* Replacing spaces with underscores

Example:

`Order ID` → `order_id`

`Customer Name` → `customer_name`

### 4. Data Type Conversion

The `order_date` column was converted from object format to datetime format using Pandas.

## Data Analysis

The cleaned dataset was analyzed using Pandas GroupBy operations.

The analysis included:

* Total sales by region
* Total sales by product
* Total sales by category
* Total sales by salesperson
* Average sales
* Minimum and maximum sales
* Number of orders by region

## Pivot Table Analysis

Pivot Tables were created to generate summary reports including:

* Sales by Region and Category
* Sales by Region and Product
* Salesperson Performance

## Business Questions

The project answers the following questions:

* Which region generated the highest sales?
* Which product generated the highest sales?
* Which category performed best?
* Which salesperson achieved the highest sales?
* What is the total sales amount?

## Technologies Used

* Python
* Pandas

## Key Pandas Concepts Used

* `read_csv()`
* `info()`
* `isnull()`
* `fillna()`
* `duplicated()`
* `drop_duplicates()`
* `rename()`
* `astype()`
* `to_datetime()`
* `groupby()`
* `agg()`
* `pivot_table()`
* `idxmax()`

## Project Workflow

Dirty Dataset

↓

Data Inspection

↓

Handle Missing Values

↓

Remove Duplicate Records

↓

Standardize Column Names

↓

Convert Data Types

↓

GroupBy Analysis

↓

Pivot Table Reports

↓

Business Insights

## Key Learning Outcomes

Through this project, I learned how to clean and prepare a real-world dataset for analysis using Pandas. I also gained practical experience in identifying data quality issues, performing data analysis using GroupBy, creating Pivot Table reports, and generating meaningful business insights.

## Author

Jeevanantham

Aspiring Data Analyst
