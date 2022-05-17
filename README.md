# ETL_Project 

The aim of our project was to extract, transform and load data to a database from 4 different CSV sources regarding world happiness for further data analysis.

The original 4 data sources used were: 

- world-happiness-report.csv
- world-happiness-report-2021.csv
- population_by_country_2020.csv
- wikipedia-iso-country-codes.csv

# Transformation

In order to transform the public data and use it in our study we performed the following:

Used Pandas functions in Jupyter Notebook to load all three CSV files.
Reviewed the files and transformed into data frames
Use of Heatmap for visual display of data
- Dropping null values for consistency
- Drop redundant data columns in Happiness datasets
- Removed Countries less than 50K pop and matched UN country code list. 

# Data Source

- Happiness index dataset on Kaggle
- Global Population dataset on Kaggle
- Country ISO code list on Wikipedia



# Load 

As part of normalisation, a yearly calander has been added as a reference table.
- Country used as Primary Key between data tables
- The use case dictates that this DB will expand

The last step was to transfer our final output into a Database. We created a database and respective table to match the columns from the final Panda's Data Frame using Postgres database using PG admin to store our original clean data sets. We reconnected to the database and generated additional tables for the data frames.

# Code Snapshots and Results 

# Links


![mail-icon-in-flat-style-email-symbol-in-flat-style-vector-28061204](https://user-images.githubusercontent.com/24882457/168715260-43b77fb5-563e-4ce3-b264-c43ab5529e53.jpg)
