# Movies-ETL

## Overview of Movies-ETL Analysis
Movies-ETL project collects movies dataset from multiple resources and create ETL piplelines from raw data to SQL database. We use Python to extract data from disparate sources, use Pandas to clean and transform data and load data with PostgreSQL. Our goal is to perform ETL on serveral movie datasets to predict popular films for a streaming service. 

## Analysis and Challenges
### Extra Datasets
- Extract Wikipedia data from JSON library
- Use Pandas library to create DataFrames
- Use Numpy library for converting data types.
- Extract the Kaggle data and inspect data type.

### Transform and Merge Datasets
- Data-Cleaning Strategies
  - Iterative process for cleaning datasets
  - Investigate the Wikipedia Data 
  - Create functions to clean data
  - Remove duplicate data
  - Make a plan to convert and parse the data
  - Write regular expressions to filter datasets.

- Merge Wikipedia and Kaggle Metadata
  - Transform and Merge Rating Data
### Load Datasets
- Connect Pandas and SQL.

## Results
We create an ETL function to read three data files. Extract and Transform Wikipedia Data and Kaggle Data in order to better perform our analysis. We transform the data into a consistent structure and load datasets to PostgreSQL. Connected with PostgreSQL, movies table contains 6,052 rows data and ratings table has 26,024,289 rows. Datasets are clean and ready to perform analysis.



