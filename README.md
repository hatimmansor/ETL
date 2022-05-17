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
<img src="https://user-images.githubusercontent.com/24882457/168723609-6c473082-06b2-4a0d-bca7-be6ad131d0e5.png" title="Data engineering – SCHEMA DIAGRAM">

# Links


<img src="https://user-images.githubusercontent.com/24882457/168723224-ecbdb402-be01-453d-9cb5-282424f7418a.png" width="20" height="20" title=" Hatims email"><Hatimf2004@gmail.com>


<img src="https://user-images.githubusercontent.com/24882457/168716629-b90f784a-534f-418c-89fd-28e91c4830fa.png" width="20" height="20" title="Linkedin Profile"><https://www.linkedin.com/in/hatim-mansor-a420ab102/>

