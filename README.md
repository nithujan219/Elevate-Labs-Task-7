# Elevate-Labs-Task-7

Objective
The goal of this task is to extract and summarize basic sales information from a small SQLite database using SQL and Python. We aim to:

Connect to a local SQLite database

Run simple SQL queries

Display results using print statements and bar charts

Tools Used
Python

SQLite (via sqlite3)

Pandas

Matplotlib

Jupyter Notebook or Python Script (.ipynb or .py)

Dataset
The SQLite database (sales_data.db) contains a single table:

sales

product (TEXT)

quantity (INTEGER)

price (REAL)

What the Script Does
Connects to the SQLite database using sqlite3

Runs an SQL query to get:

Total quantity sold per product

Total revenue per product

Loads the query result into a pandas DataFrame

Prints the summary

Visualizes revenue data using a bar chart
