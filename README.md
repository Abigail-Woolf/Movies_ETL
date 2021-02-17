# Movies ETL
Extract, Transform, Load

## Project Overview
This repository explores the process of extracting, transforming, and loading data. The ETL process is standard when working with large datasets. It helps the programmer utilize the tools they were given in the most effiecient and timely way possible. For this project, I created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. Also, adding try-except blocks will make the automated ETL script more robust to errors.

## File Contents
| Folder | Contents |
|--------|----------|
| Resources | Raw kaggle data and Wiki JSON |
| Final_ETL | Final notebook and script for automated ETL |


Create an automated ETL pipeline.
Extract data from multiple sources.
Clean and transform the data automatically using Pandas and regular expressions.
Load new data into PostgreSQL.
Instructions
For this task, assume that the updated data will stay in the same formats: Wikipedia data in JSON format and Kaggle metadata and rating data in CSV formats. Follow these steps:

Create a function that takes in three arguments:
Wikipedia data
Kaggle metadata
MovieLens rating data (from Kaggle)
Use the code from your Jupyter Notebook so that the function performs all of the transformation steps. Remove any exploratory data analysis and redundant code.
Add the load steps from the Jupyter Notebook to the function. You’ll need to remove the existing data from SQL, but keep the empty tables.
Check that the function works correctly on the current Wikipedia and Kaggle data.
Document any assumptions that are being made. Use try-except blocks to account for unforeseen problems that may arise with new data.
