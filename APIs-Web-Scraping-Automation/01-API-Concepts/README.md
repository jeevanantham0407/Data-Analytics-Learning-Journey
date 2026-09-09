# API Concepts

## Overview

This section covers the fundamental concepts of Application Programming Interfaces (APIs) and their importance in data analytics.

## What is an API?

API stands for Application Programming Interface. It allows different software applications to communicate with each other and exchange data.

## Why APIs are Useful in Data Analytics

APIs allow data analysts to collect data programmatically from external applications and services. This reduces manual data collection and makes it possible to build repeatable data workflows.

Typical workflow:

Python → API → JSON → Pandas → Data Cleaning → Analysis → Visualization

## Concepts Learned

* API
* Client
* Server
* API Endpoint
* Request
* Response
* HTTP
* HTTP Methods
* HTTP Status Codes
* JSON
* API Keys

## HTTP Methods

| Method | Purpose               |
| ------ | --------------------- |
| GET    | Retrieve data         |
| POST   | Create data           |
| PUT    | Update data           |
| PATCH  | Partially update data |
| DELETE | Delete data           |

## Important Status Codes

| Status Code | Meaning            |
| ----------: | ------------------ |
|         200 | Successful request |
|         201 | Resource created   |
|         400 | Bad request        |
|         401 | Unauthorized       |
|         403 | Forbidden          |
|         404 | Resource not found |
|         500 | Server error       |

## Practice Files

* `api_concepts.ipynb`
* `http_methods.ipynb`
* `status_codes.ipynb`
* `json_example.ipynb`

## Key Learning

APIs provide a programmatic way to access external data. Understanding API requests, responses, endpoints, HTTP methods, status codes, and JSON is the foundation for collecting and processing data using Python.