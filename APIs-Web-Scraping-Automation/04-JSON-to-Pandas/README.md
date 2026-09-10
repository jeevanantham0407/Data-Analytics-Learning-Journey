# Part 4 – JSON to Pandas

## Overview

This part focuses on working with JSON data in Python and converting API responses into Pandas DataFrames for data analysis.

The main objective is to understand how raw API data can be converted into a structured and analysis-ready format.

## Topics Covered

* JSON basics
* JSON strings and Python dictionaries
* JSON lists
* Nested JSON
* Extracting values from nested JSON
* API responses using `requests`
* Converting API JSON into Pandas DataFrames
* Extracting nested fields into separate columns
* Selecting relevant columns for analysis

## Practice Files

### 01_json_basics.py

Practiced converting JSON strings into Python dictionaries and lists using `json.loads()`.

### 02_nested_json.py

Worked with nested JSON structures and extracted values from multiple levels.

### 03_api_to_dataframe.py

Retrieved user data from the JSONPlaceholder API, converted the response into a Pandas DataFrame, extracted nested address and company information, and created a structured dataset for analysis.

## Technologies Used

* Python
* Requests
* JSON
* Pandas
* REST API
* VS Code

## Data Workflow

```text
API
 ↓
Python Requests
 ↓
JSON Response
 ↓
Python List / Dictionary
 ↓
Pandas DataFrame
 ↓
Structured Data
 ↓
Data Analysis
```

## Key Learning

This part helped me understand how API data can be transformed from nested JSON into a structured Pandas DataFrame.

This is an important step in data analytics because real-world data is often collected from APIs in JSON format and needs to be extracted, transformed, and structured before analysis and visualization.

## Next Step

The next part will focus on working with a real-world weather API and collecting practical weather data using Python.
