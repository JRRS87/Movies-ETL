# Movies-ETL

##Overview of the Project

This project will create an automated pipeline that takes in new data, from Wikipedia data, 
Kaggle metadata and the MovieLens rating data. Then performs the appropriate transformations 
and loads the data into an existing PostgreSQL database.

For this analysis, we used the following breakdown:

- write an ETL function to read three data files,
- extract and transform the Wikipedia data,
- extract and transform the Kaggle and rating data,
- load the data to a PostgreSQL Movie Database.

##Results

The function takes the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates 
three separate DataFrames.
We consolidated the redundant data, filtered, removed the duplicates and formatted the Wikipedia 
data.

##Summary

The ETL function does transforms and merges the data and loads it into two updatable PostgreSQL 
dataset tables ready to be used by the hackathon participants for their analysis.
