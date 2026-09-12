
# APIs, Web Scraping & Automation

## Overview

This repository contains my practical learning and projects related to API integration, HTTP requests, JSON data processing, web scraping, data collection automation, Pandas, CSV handling, and basic data analysis using Python.

The goal of this learning path was to understand how external data can be collected from APIs and websites, transformed into structured datasets, stored for future use, and prepared for analysis.

## Learning Objectives

* Understand API concepts and client-server communication
* Work with HTTP requests using Python
* Understand HTTP methods and status codes
* Process JSON data
* Extract data from APIs
* Convert API responses into Pandas DataFrames
* Collect real-world weather data using an API
* Store API data in CSV files
* Automate repeated data collection
* Build historical datasets
* Understand basic web scraping
* Extract information from HTML pages using BeautifulSoup
* Convert scraped data into structured datasets
* Perform data cleaning and basic analysis using Pandas

## Repository Structure

```text
APIs-Web-Scraping-Automation/
│
├── README.md
├── requirements.txt
│
├── 01-API-Concepts/
│   ├── README.md
│   ├── api_concepts.py
│   ├── http_methods.py
│   ├── status_codes.py
│   └── json_example.py
│
├── 02-Real-API-JSONPlaceholder/
│   ├── README.md
│   ├── 01_get_users.py
│   ├── 02_get_single_user.py
│   ├── 03_get_posts.py
│   ├── 04_get_single_post.py
│   ├── 05_get_comments.py
│   ├── 06_extract_data.py
│   ├── 07_filter_data.py
│   ├── 08_query_parameters.py
│   └── 09_error_handling.py
│
├── 03-HTTP-Requests/
│   ├── README.md
│   ├── 01_get_request.py
│   ├── 02_status_codes.py
│   ├── 03_response_text.py
│   ├── 04_response_json.py
│   ├── 05_query_parameters.py
│   ├── 06_headers.py
│   ├── 07_timeout.py
│   └── 08_error_handling.py
│
├── 04-JSON-to-Pandas/
│   ├── README.md
│   ├── 01_json_basics.py
│   ├── 02_nested_json.py
│   └── 03_api_to_dataframe.py
│
├── 05-Open-Meteo-API/
│   ├── README.md
│   └── weather_api.py
│
├── 06-API-to-CSV/
│   ├── README.md
│   └── weather_to_csv.py
│
├── 07-Automation/
│   ├── README.md
│   └── automated_weather_data.py
│
├── 08-Mini-Project/
│   ├── README.md
│   ├── weather_data_fetcher.py
│   └── weather_data.csv
│
├── 09-Web-Scraping/
│   ├── README.md
│   ├── 01_get_webpage.py
│   ├── 02_beautifulsoup_basics.py
│   ├── 03_extract_titles.py
│   ├── 04_extract_links.py
│   ├── 05_extract_data.py
│   ├── 06_scraping_to_pandas.py
│   └── quotes.csv
│
└── 10-Scraped-Data-Analysis/
    ├── README.md
    ├── 01_read_csv.py
    ├── 02_data_exploration.py
    ├── 03_data_cleaning.py
    └── 04_basic_analysis.py
```

## Topics Covered

### 1. API Fundamentals

Learned the basic concepts of APIs and how applications communicate with external services.

Topics included:

* API definition
* Client-server architecture
* API endpoints
* API requests and responses
* API keys
* HTTP methods
* HTTP status codes
* JSON data

### 2. Working with APIs

Used the JSONPlaceholder API to practice real API requests using Python.

Topics included:

* GET requests
* Retrieving multiple records
* Retrieving individual records
* Query parameters
* Nested JSON
* Data extraction
* Filtering API data
* Basic error handling

### 3. HTTP Requests with Python

Used the Requests library to understand how Python communicates with web services.

Topics included:

* `requests.get()`
* Response objects
* Status codes
* `response.text`
* `response.json()`
* Query parameters
* Headers
* Request timeouts
* Exception handling

### 4. JSON to Pandas

Learned how API responses can be transformed into structured tabular data.

Topics included:

* JSON structures
* Python dictionaries and lists
* Nested JSON
* Pandas DataFrames
* Extracting nested fields
* Creating analysis-ready columns

### 5. Real-World Weather API

Worked with the Open-Meteo API to collect real-world weather information.

Collected data such as:

* Temperature
* Relative humidity
* Apparent temperature
* Precipitation
* Wind speed
* Location coordinates

### 6. API Data to CSV

Learned how to store API data in a reusable format.

Workflow:

```text
API
↓
JSON Response
↓
Data Extraction
↓
Pandas DataFrame
↓
CSV File
```

### 7. Data Collection Automation

Learned the basic concepts of automating repeated data collection.

Implemented:

* Automatic API requests
* Timestamp generation
* CSV file checking
* Appending new records
* Historical data collection

### 8. Mini Project – Automated Weather Data Fetcher

Built a Python-based mini project that collects weather information from the Open-Meteo API and stores the data in CSV format.

The project combines:

* API requests
* JSON processing
* Data extraction
* Pandas
* CSV storage
* Timestamps
* Historical data
* Basic analysis

### 9. Web Scraping

Learned how to collect information from HTML web pages using Requests and BeautifulSoup.

Topics included:

* Retrieving HTML pages
* Parsing HTML
* Finding HTML elements
* Extracting text
