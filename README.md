# Movies-ETL-Practice
Module 8 Challenge

## Overview of Project

The overview of this project is to use principles learned during the class exrecise to Etract data, Transform it to a format that is readily usable and readible and Load it to a location that is accessable for data analysis that will be used to assist in decision making. In this case, we are pulling data from Wikipedia and Kaggle data from their respective locations.  We are then processing each data file by removing unnecessary columns, creating uniformed column formatting, performing joins to merge the two data sets together, remove redundant columns, and then upload the finalized clean datasets into a Postgres SQL database.

### ETL Function Deliverable

For the ETL Function Deliverable we were required to do the following:

  * Write an ETL function that reads in the three data files.
  * Manages both csv files and JSON files.
  * Creates three separate data files that will be read into DataFrames.

### ETL Clean Wiki Movies Deliverable
For the ETL Clean Wiki Movies Deliverable we were required to do the following:
  * Extract and transform the Wikipedia data so you can merge it with the Kaggle metadata.
  * Extracting the IMDb IDs using a regular expression string and dropping duplicates.
  * Create different functions to clean movie data to account for movie titles based on language and to merge and rename duplicate column names.
  * Create ETL function that pulls in data files, discards unnecessary columns, format ID columns, create forms to uniform currency information.
  * Create try-except function for error handling.
  * Clean budget columns, running time columns, release date, and box office information.

### ETL Clean Kaggle Data Deliverable
For the ETL Clean Kaggle Deliverable we were required to add the following to the function created in the previous deliverables:
  * Extract and transform the Kaggle metadata and MovieLens rating data.
  * Convert the transformed data into separate DataFrames. 
  * Merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame
  * Create a DataFrame by merging Movies DataFrames and Movie Lens DataFrames
  
### ETL Create Database Deliverable
For the ETL Create Database Deliverable to do the following:
  * Add to the function code to connect to Postgresql data base using sqlalchemy library and to_sql method.
  * Using code created to communicate with database, add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
  * Verify completion of data transfer and load by running two quieries. One that returns count of rows in Movies table and count of rows in Ratings table.
