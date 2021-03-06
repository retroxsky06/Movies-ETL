# Movies-ETL
##### Module 8 Challenge
## Project Overview
Amazing Prime, a fictional online streaming company is interested in developing an algorithm to predict which low budget movies will become popular. The team is tasked to create datasets for Amazing Prime's hackathon. Movie data from Wikipedia Movie and Kaggle were collected.

The purpose of this project is to create an automated pipeline that takes in new movie data, performs the appropriate transformations, and loads the data into existing tables.  The project consists of four deliverables, with each outcome building upon the other- from extracting data and function testing, cleaning and transforming, and to finally creating  and loading the database in SQL.  
### Software & Resources
- Python 3.8
- PostgreSQL 11.1
- pgAdmin 5.4
- Movie data sourced from Wikipedia Movie and Kaggle

### Deliverables of the Project
- Deliverable 1: Write an ETL Function to Read Three Data Files
- Deliverable 2: Extract and Transform the Wikipedia Data
- Deliverable 3: Extract and Transform the Kaggle data
- Deliverable 4: Create the Movie Database

## Results
The analysis was completed with the new ETL function and the data was successfully added to a PostgreSQL database.

#### Number of Rows: Movies Database
![fig](https://github.com/retroxsky06/Movies-ETL/blob/main/Resources/movies_query.png)
#### Number of Rows: Ratings Database
![fig2](https://github.com/retroxsky06/Movies-ETL/blob/main/Resources/ratings_query.png)

##### Query used to retrieve number of rows from movies and ratings database
SELECT COUNT (*) FROM movies;
SELECT COUNT (*) FROM ratings;
