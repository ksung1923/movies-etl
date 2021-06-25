# Movie ETL Analysis


## Overview of Movie ETL Analysis
Amazing prime is a platform for streaming movies and TV shows. The worlds largest online streamer. The team would like to develop an algorithm to predict which low budget movie being release will be popular so they can buy the stream rights. Amazing prime has sponsored a hack-a-thon to provide a clean dataset of movie data and asking participants to predict the popular pictures. Britta has been tasks to create the dataset from two data sources.

1. Scrape and extract Kaggle data off Wikipedia for all movies released since 1990. I extracted and scraped Wikipedia data stored as a JSON and Kaggle data stored in CSVs. 
2. Rating data from the Movie Land's Webisde 

I extracted the data from the two sources, transformed into one clean dataset, and finally load that data set into a SQL table. I took it one step further and created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 


## Resources and Software 
-PostgreSQL
-Jupyter Notebooks

Data Sources: 
1. Wikipedia Data
2. Kaggle Medadata 
3. MovieLens Rating Data


## Results and Summary
I created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. I performed the ETL process and added the data to a PostgreSQL database. The two tables created are "movies" and "ratings". Please see the row count of the data in PostgreSQL. 

![movie](https://github.com/ksung1923/movies-etl/blob/a7145315e92bd1716d6cc75903ce19ce2fb029da/Resources/movies_query.PNG) 


![ratings](https://github.com/ksung1923/movies-etl/blob/a7145315e92bd1716d6cc75903ce19ce2fb029da/Resources/ratings_query.PNG) 