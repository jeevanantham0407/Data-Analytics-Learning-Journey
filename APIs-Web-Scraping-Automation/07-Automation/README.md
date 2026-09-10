# Part 7 – API Data Automation

## Overview

This part focuses on automating the process of collecting weather data from an API and storing multiple records in a CSV file.

Instead of replacing the existing data each time, new records are appended to the CSV file to build a historical dataset.

## Objectives

* Automate API data collection
* Add timestamps to collected data
* Append new records to an existing CSV file
* Build a historical dataset
* Understand basic data collection automation

## Practice File

### automated_weather_data.py

The program:

1. Sends a request to the Open-Meteo API
2. Retrieves current weather information
3. Extracts the required fields
4. Adds a timestamp
5. Creates a Pandas DataFrame
6. Checks whether the CSV file already exists
7. Appends new data when the file exists
8. Creates a new file when it does not exist

## Output File

### weather_history.csv

The CSV file stores multiple weather records collected at different times.

Example fields include:

* Timestamp
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
* OS module
* VS Code

## Data Workflow

Weather API
↓
API Request
↓
JSON Response
↓
Data Extraction
↓
Pandas DataFrame
↓
Timestamp
↓
Append to CSV
↓
Historical Dataset

## Key Learning

This part introduced the basic concept of data collection automation.

Automated data collection is useful in Data Analytics because regularly collected data can be stored as historical records and later used to identify trends, patterns, and changes over time.

## Next Step

The next part combines API requests, Pandas, CSV storage, and basic analysis into a complete weather data mini project.
