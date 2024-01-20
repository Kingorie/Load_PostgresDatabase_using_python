# Overview

This Python script is designed to facilitate the process of reading multiple CSV files, creating a directory, copying these files into the directory, and then uploading the data from these CSV files into a PostgreSQL database. The script uses the Pandas library for handling data and the SQLAlchemy library to connect and interact with the PostgreSQL database.

# Prerequisites

Make sure you have the following installed:

Python
Pandas library
SQLAlchemy library
PostgreSQL database

# Usage

To utilize the script: 
* Scan and compile CSV files from the current directory. 
* Create a 'datasets' directory and copy CSV files. 
* Read files into Pandas DataFrames, clean table and column names, and upload to a PostgreSQL database. Ensure backups for table replacement.

# Notes

* Make sure to install the required libraries using pip install pandas sqlalchemy if you haven't already.
* Modify the database connection details in the script to match your PostgreSQL setup.
* The script assumes that the CSV files are in the same directory as the script.
* Check the PostgreSQL database for successfully uploaded tables.

Feel free to adapt the script according to your specific requirements and data sources.
