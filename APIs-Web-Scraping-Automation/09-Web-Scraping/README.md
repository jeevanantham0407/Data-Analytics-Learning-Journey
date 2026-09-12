# Part 9 – Web Scraping with BeautifulSoup

## Overview

This part focuses on collecting structured data from a web page using Python, Requests, and BeautifulSoup.

The Quotes to Scrape website was used as a practice source to understand how HTML content can be accessed, parsed, and converted into structured data.

## Objectives

* Understand basic web scraping
* Send HTTP requests to a web page
* Parse HTML using BeautifulSoup
* Find HTML elements and attributes
* Extract quotes, authors, tags, and links
* Convert scraped data into a Pandas DataFrame
* Save scraped data as a CSV file

## Practice Files

### 01_get_webpage.py

Retrieves the HTML content of the web page using Requests.

### 02_beautifulsoup_basics.py

Introduces BeautifulSoup and demonstrates how to access page titles and headings.

### 03_extract_titles.py

Extracts quotes and authors from the web page.

### 04_extract_links.py

Extracts links, link text, and URLs from the page.

### 05_extract_data.py

Extracts complete quote records including quotes, authors, and tags.

### 06_scraping_to_pandas.py

Converts the scraped data into a Pandas DataFrame and exports it to CSV.

## Output

### quotes.csv

The scraped dataset contains:

* Quote
* Author
* Tags

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* HTML
* CSV
* VS Code

## Data Workflow

Web Page
↓
HTTP Request
↓
HTML Response
↓
BeautifulSoup
↓
Data Extraction
↓
Pandas DataFrame
↓
CSV File

## Key Learning

This part provided practical experience in collecting data from web pages and converting unstructured HTML content into structured tabular data.

Web scraping can be useful in Data Analytics when information is publicly available on web pages and needs to be collected for further cleaning, analysis, and visualization.
