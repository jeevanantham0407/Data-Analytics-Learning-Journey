# Part 3 – HTTP Requests with Python

## Overview

This part focuses on working with HTTP requests using Python's `requests` library. The goal is to understand how Python communicates with APIs, handles responses, sends parameters and headers, and manages request errors.

## Topics Covered

* GET requests
* HTTP status codes
* `response.text`
* `response.json()`
* Query parameters
* HTTP headers
* Request timeout
* `raise_for_status()`
* Error handling

## Practice Files

### 01_get_request.py

Learned how to send a GET request using `requests.get()` and check the API response.

### 02_status_codes.py

Practiced checking HTTP status codes such as `200` and `404`.

### 03_response_text.py

Learned how to access the raw API response using `response.text`.

### 04_response_json.py

Learned how to convert an API response into Python dictionaries and extract required fields.

### 05_query_parameters.py

Practiced sending query parameters using the `params` argument to request specific API data.

### 06_headers.py

Learned how HTTP headers provide additional information with an API request.

### 07_timeout.py

Learned how to set a timeout so a program does not wait indefinitely for an API response.

### 08_error_handling.py

Practiced using `raise_for_status()` and `try-except` to handle API request errors safely.

## Technologies Used

* Python
* Requests Library
* JSON
* REST APIs
* VS Code

## Key Learning

This part helped me understand the complete HTTP request process:

```text
Python
   ↓
HTTP Request
   ↓
API Server
   ↓
HTTP Response
   ↓
Status Code
   ↓
JSON / Text
   ↓
Python Data
```

Understanding HTTP requests is important for Data Analytics because APIs are a common source of real-world data. Proper request handling helps collect reliable data before cleaning, transforming, analyzing, and visualizing it.

## Next Step

The next part will focus on converting JSON API data into Pandas DataFrames for further data analysis.
