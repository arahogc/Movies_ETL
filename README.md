# Movies_ETL

The purpose of this excercise was to practice taking data and cleaning it up for databases. The resources that were cleaned were the wikipedia_movies.json, movies_metadata.csv, and ratings.csv. However, the ratings.csv was too large for Github, and despite some attempts at alternatives to upload it, it was unsuccessful to load. One can download the data here: https://www.kaggle.com/rounakbanik/the-movies-dataset 

First, each individual file was cleaned (e.g. removing "bad" data, removing tv shows, making rows with in columsn are more uniform, etc) using a mix of functions, list comprehensions, lambdas, and regex. Second, tables were merged together after the data was cleaned, and then, finally, uploaded to as a database. 
