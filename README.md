# Movies_ETL
Using the ETL process to transfer movie data from an online source through Python and into SQL.

## Project Overview
Using Python to extract the JSON and csv files from the local folder. Then Python is used to clean up the data and transform it into a useablee dataset. Lastly, Python is used to load the dataset into SQL.

The challenge project uses the same process but implementing the entire project as one working function. So when the names of the dataset are inputted into the function, it automatically extracts, transforms, and loads the datasets.

## Resources
- Data Source: wikipedia.movies.json, movies_metadata.csv, ratings.csv
- Software: Python 3.6.1, conda 4.7.12, PostgreSQL 11.5, pgAdmin4 4.16

## Summary

The project was to create a clean movies dataset that can be used in SQL. The data was grabbed from Wikipedia and Kaggle. The main focus on the project was to use the ETL process to move the data from online and into a working SQL dataset using Python.

1. First downloaded the three different datsets from their respective websites onto a local folder
2. Loaded the datasets into Python
3. Looked through the datasets and searched for any problems and data to clean up and fix.
4. Transformed the datasets by combining columns, deleting uncessary columns, fixing header titles, and changing the datatype of the data
5. Prepared to merge the edited wikipedia dataset and kaggle metadata dataset ny looking at overlaping information
6. Merged the two datasets and by right merging into the Kaggle data and filling empty holes with the Wiki data
7. Finally loaded the movies dataframe and ratings dataframe into SQL by using sqlalchemy and psycopg2
8. Opened up SQL and checked if the datsets loaded properly into SQL

The challange project is using the exact same ETL process but making it into a working function. The function would have the entire ETL code in it. So when the file names are placed as the variables in function, the function would then run the entire ETL code and finish by loading the files onto SQL.

1. First looked through the previous code to see which lines of code were used for the ETL process and which lines were not important.
2. From there the code was placed into a function with three variable for the data files.
3. The function was tested to see if everything worked properly.

## Analysis

The ETL process is a powerful process where data from online sources can be extracted, transformed, and loaded to be used and analyzed. 
Results from transforming the dataset showed that the wikipedia dataset was very inconsistent and shouldnt be heavily used in the future. The reason being that it is an open website where anyone can write in data and there is no specific formatting. 
Functions are also very powerful tools that can clean up the code for any project. Functions are also useful since it can be reused with different dataset with minor tweaks within the function code. 