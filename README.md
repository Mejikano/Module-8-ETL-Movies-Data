# Module-8-ETL-Movies-Data

### Resources
- Data source: movies_metadata.csv (Kaggle), wikipedia-movies.json (Wikipedia), ratings.csv (MovieLens)
- Software: Jupyter Notebook 6.3.0, PostgreSQL 11, pgAdmin 5.5

## Overview
Amazing Prime company will be running a hackaton and requires structured data stored for its comsumption, this project automates a process to take the data and store it in a database via ETL: Extract-Transform-Load script that performs the appropriate transformations, and loads the data into existing tables. The input files used come from files—Wikipedia data, Kaggle metadata, and the MovieLens rating data and python scripts performs the ETL process by adding the data to a PostgreSQL database.

## Results
Final outcome of the process populate two target tables: movies and ratings

![Movies Table Query - Total Records](https://github.com/Mejikano/Module-8-ETL-Movies-Data/blob/main/Resources/movies_query.png)

![Ratings Table Query - Total Records](https://github.com/Mejikano/Module-8-ETL-Movies-Data/blob/main/Resources/ratings_query.png)
