# Part 6 – API Data to CSV

## Overview

This part focuses on converting weather API data into a structured Pandas DataFrame and saving it as a CSV file.

The goal is to understand how data collected from an API can be stored in a reusable format for further analysis.

## Objectives

* Collect data from an API
* Extract required weather fields
* Create a Pandas DataFrame
* Convert API data into tabular format
* Save the DataFrame as a CSV file
* Understand the API-to-CSV workflow

## Practice File

### weather_to_csv.py

The program retrieves current weather data from the Open-Meteo API, extracts the required fields, creates a Pandas DataFrame, and saves the result as `weather_data.csv`.

## Output File

### weather_data.csv

The CSV contains structured weather information such as:

* City
* Latitude
* Longitude
* Temperature
* Humidity
* Feels Like Temperature
* Precipitation
* Wind Speed

## Technologies Used

* Python
* Requests
* Pandas
* JSON
* CSV
* VS Code

## Data Workflow

Open-Meteo API
↓
Python Requests
↓
JSON Response
↓
Data Extraction
↓
Pandas DataFrame
↓
CSV File

## Key Learning

This part helped me understand how API data can be transformed into a structured tabular format and stored as a CSV file.

This workflow is commonly used in Data Analytics when collecting data from external sources before performing data cleaning, analysis, and visualization.

## Next Step

The next part focuses on automating the process of collecting and storing API data.
