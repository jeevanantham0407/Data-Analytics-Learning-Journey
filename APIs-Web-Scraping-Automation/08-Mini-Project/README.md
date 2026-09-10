# Part 8 – Automated Weather Data Fetcher

## Project Overview

The Automated Weather Data Fetcher is a Python-based mini project that collects current weather information from the Open-Meteo API and stores the collected data in a CSV file.

The project combines API data collection, JSON processing, Pandas, CSV storage, and basic data analysis into one workflow.

## Project Objectives

* Collect real-world weather data using an API
* Process JSON API responses
* Extract required weather information
* Convert API data into a Pandas DataFrame
* Store weather records in a CSV file
* Build historical weather data
* Perform basic analysis using Pandas

## Data Collected

The project collects:

* Timestamp
* City
* Latitude
* Longitude
* Temperature
* Humidity
* Feels Like Temperature
* Precipitation
* Wind Speed

## Project Files

### weather_data_fetcher.py

Main Python program responsible for:

* Connecting to the Open-Meteo API
* Sending HTTP requests
* Processing the JSON response
* Extracting weather information
* Creating a Pandas DataFrame
* Saving weather records into a CSV file

### weather_data.csv

Stores the collected weather records and provides historical data for further analysis.

## Technologies Used

* Python
* Requests
* Pandas
* JSON
* CSV
* REST API
* VS Code

## Project Workflow

Open-Meteo API
↓
HTTP Request
↓
JSON Response
↓
Data Extraction
↓
Pandas DataFrame
↓
CSV Storage
↓
Historical Data
↓
Data Analysis

## Basic Analysis

The project performs basic analysis on the collected weather data, including:

* Average Temperature
* Maximum Temperature
* Minimum Temperature
* Average Humidity
* Highest Temperature Record

## Key Learning

This project provided practical experience in building a simple data collection pipeline using Python.

It demonstrated how external API data can be collected, transformed into structured data, stored for historical use, and analyzed using Pandas.

The project also strengthened my understanding of how API-based data collection can be connected with the broader Data Analytics workflow.

## Future Improvements

* Collect data automatically at regular intervals
* Add more cities
* Collect historical weather information
* Add weather condition descriptions
* Create visualizations using Matplotlib
* Build a Power BI dashboard
* Analyze weather trends over time

## Conclusion

This mini project demonstrates a complete workflow from API data collection to structured storage and basic analysis.

It provides a practical foundation for building larger data analytics projects using real-world external data sources.
