# Movies_ETL

### Overview of Analysis
For this analysis, I created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. I used one function that takes in three files: Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

### Process

  1. Write an ETL Function to Read Three Data Files
  2. Extract and Transform the Wikipedia Data
  3. Extract and Transform the Kaggle Data
  4. Create the Movie Database with two tables

### Results
Using Python, I cleaned, merged datasets, and exported two new tables into PostgresSQL. 

***Write an ETL Function to Read Three Data Files***

      1. File 1: wiki_movies_df
      
<p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/Movies_ETL/blob/main/Resources/wiki_movies_df.png">
  
      2. File 2: kaggle_metadata
  
<p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/Movies_ETL/blob/main/Resources/kaggle_metadata.png">
  
      3. File 3: ratings
  
<p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/Movies_ETL/blob/main/Resources/ratings.png">
  
***Extract & transform Wikipidia and Kaggle Data***
  
[Extract & Transform Wikipedia Data](https://github.com/molivajimenez22/Movies_ETL/blob/main/ETL_clean_wiki_movies.ipynb)
 
<p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/Movies_ETL/blob/main/Resources/Clean_Movies.png">

<p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/Movies_ETL/blob/main/Resources/clean_movies2.png">
  
[Extract & Transform Kaggle Data](https://github.com/molivajimenez22/Movies_ETL/blob/main/ETL_clean_kaggle_data.ipynb)
  
  <p align="center" width="100%">
    <img width="66%" src="https://github.com/molivajimenez22/Movies_ETL/blob/main/Resources/Clean_Kaggle2.png">
