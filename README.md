# ETL_Project: 
The aim of our project was to extract, transform and load data to a database from 4 different CSV sources regarding world happiness for further data analysis.

The original 4 data sources used were: 

- world-happiness-report.csv
- world-happiness-report-2021.csv
- population_by_country_2020.csv
- wikipedia-iso-country-codes.csv


# Data Source:
- Happiness index dataset on Kaggle
- Global Population dataset on Kaggle
- Country ISO code list on Wikipedia


# Technologies/Tools: 
&#10004;Pandas      &#10004;Sqlalchemy      &#10004;Matplotlib      &#10004;Seaborn
&#10004;Python


# Load: 
As part of normalisation, a yearly calander has been added as a reference table.
- Country used as Primary Key between data tables
- The use case dictates that this DB will expand

The last step was to transfer our final output into a Database. We created a database and respective table to match the columns from the final Panda's Data Frame using Postgres database using PG admin to store our original clean data sets. We reconnected to the database and generated additional tables for the data frames.


# Transformation:
In order to transform the public data and use it in our study we performed the following:
Pandas functions is used in Jupyter Notebook to load all three CSV files.
Reviewed the files and transformed into data frames
Use of Heatmap for visual display of data
- Dropping null values for consistency
- Drop redundant data columns in Happiness datasets
- Removed Countries less than 50K pop and matched UN country code list. 


# Code Snapshots and Results: 
<table>
  <tr>
    <th style="text-align:center">Data engineering – SCHEMA DIAGRAM</td>
     <th style="text-align:center">Table Nill Value Menu</td>
     
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/24882457/168723999-368049e6-2fd3-4727-857a-010f53f80b3d.png" width=550 height=350 title="Data engineering – SCHEMA DIAGRAM"></td>
    <td><img src="https://user-images.githubusercontent.com/24882457/168761449-8aacb912-40dc-4157-b4b0-48d3bdb95375.png" width=550 height=350 title="Table Nill Value Menu"></td>
    
  </tr>
</table>


# Contact:
<img src="https://user-images.githubusercontent.com/24882457/168723224-ecbdb402-be01-453d-9cb5-282424f7418a.png" width="20" height="20" title=" Hatims email"><Hatimf2004@gmail.com>

<img src="https://user-images.githubusercontent.com/24882457/168716629-b90f784a-534f-418c-89fd-28e91c4830fa.png" width="20" height="20" title="Linkedin Profile"><https://www.linkedin.com/in/hatim-mansor-a420ab102/>

