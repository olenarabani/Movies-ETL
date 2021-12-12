# Movies-ETL
## Background
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Overview of Project
Wikipedia has a ton of information about movies, including budgets and box office returns, cast and crew, production and distribution, and so much more. Luckily, one of Britta's coworkers created a script to go through a list of movies on Wikipedia from 1990 to 2018 and extract the data from the sidebar into a JSON. Unfortunately, her coworker can't find the script anymore and just has the JSON file. We'll need to load in the JSON file into a Pandas DataFrame.

## Deliverable 1: Write an ETL Function to Read Three Data Files

![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/wiki_movie_DF_delivery%201.png)
![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/kaggle_metadata_DF_delivery%201.png)
![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/ratings_DF_delivery%201.png)

## Deliverable 2: Extract and Transform the Wikipedia Data

![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/clean_wiki_movies_df.png)
![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/clean_wiki_movies_columns_df.png)
![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/clean_kaggle_movies_with-ratings_df.png)

## Deliverable 3: Extract and Transform the Kaggle Data

![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/kaggle_metadata_DF_delivery%201.png)
![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/clean_kaggle_wiki_movies_df.png)
![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/clean_kaggle_ratings_df.png)

## Deliverable 4: Create the Movie Database
![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/movies_query.png)
![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/importing_rows_database.png)
![This is an image](https://github.com/olenarabani/Movies-ETL/blob/main/Database_wiki_function.png)



