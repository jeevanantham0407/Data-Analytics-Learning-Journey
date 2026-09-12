# Part 10 – Scraped Data Analysis

## Overview

This part focuses on analyzing the data collected through web scraping.

The scraped quotes dataset was loaded into Pandas, explored, cleaned, and analyzed to understand the complete workflow from data collection to basic insights.

## Objectives

* Load scraped data using Pandas
* Explore the dataset
* Check rows and columns
* Identify data types
* Check missing values
* Identify duplicate records
* Clean text data
* Analyze author frequency
* Generate basic insights

## Practice Files

### 01_read_csv.py

Loads the scraped `quotes.csv` file into a Pandas DataFrame.

### 02_data_exploration.py

Explores the dataset using:

* head()
* tail()
* shape
* columns
* dtypes
* info()
* unique()
* nunique()
* isnull()

### 03_data_cleaning.py

Performs basic data cleaning by:

* Checking missing values
* Checking duplicate records
* Removing duplicates
* Removing unnecessary spaces from text fields

### 04_basic_analysis.py

Performs basic analysis including:

* Total number of quotes
* Number of unique authors
* Author frequency
* Most frequent author
* Least frequent author
* Author-specific quote analysis
* Tag count analysis

## Technologies Used

* Python
* Pandas
* CSV
* VS Code

## Data Workflow

Scraped Data
↓
CSV File
↓
Pandas DataFrame
↓
Data Exploration
↓
Data Cleaning
↓
Data Analysis
↓
Insights

## Key Learning

This part demonstrated how scraped data can be processed using a standard Data Analytics workflow.

The dataset was explored and cleaned before performing basic analysis to identify patterns such as author frequency and tag usage.

## Conclusion

Combining web scraping with Pandas provides a practical workflow for collecting external data and preparing it for analysis.

This experience strengthened the connection between data collection, data cleaning, data analysis, and Python-based analytics.
