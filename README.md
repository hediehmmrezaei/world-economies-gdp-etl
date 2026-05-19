# World Economies GDP ETL Project

This project is a simple ETL pipeline built with Python. It extracts GDP data from a web page, transforms the data into a cleaner format, and loads the final result into both a CSV file and a SQLite database.

The project focuses on practicing web scraping, data cleaning, database loading, SQL querying, and logging the progress of an ETL process.

## Project Description

The main goal of this project is to collect GDP information for countries and prepare it for analysis.

The program extracts country GDP data from an archived Wikipedia page. The original GDP values are given in millions of US dollars. During the transformation step, the values are converted into billions of US dollars and rounded to two decimal places.

After transformation, the data is saved in two formats:

- A CSV file
- A SQLite database table

The program also runs an SQL query to display countries with GDP greater than or equal to 100 billion US dollars.

## Technologies Used

The project uses the following Python libraries:

```python
from bs4 import BeautifulSoup
import requests
import pandas as pd
import numpy as np
import sqlite3
from datetime import datetime

Skills Practiced
This project helped practice the following skills:
Python programming
Web scraping
HTML parsing with BeautifulSoup
Data extraction
Data cleaning
Data transformation
Working with Pandas DataFrames
Saving data to CSV files
Creating and using SQLite databases
Running SQL queries in Python
Logging ETL progress
Organizing a project for GitHub
Project Workflow
The complete workflow of the project is:
Start ETL process
        ↓
Extract GDP data from web page
        ↓
Store extracted data in a Pandas DataFrame
        ↓
Clean and transform GDP values
        ↓
Convert GDP from millions to billions
        ↓
Save transformed data to CSV
        ↓
Connect to SQLite database
        ↓
Load data into database table
        ↓
Run SQL query
        ↓
Save progress messages in log file
        ↓
Close database connection
Conclusion
This project demonstrates a basic ETL pipeline using Python. It extracts GDP data from a web page, transforms the data into a cleaner and more useful format, and loads it into both a CSV file and a SQLite database.
The project is useful for practicing important data engineering concepts such as extraction, transformation, loading, database storage, SQL querying, and process logging.

One small change: replace this part:

```text
Hedieh
