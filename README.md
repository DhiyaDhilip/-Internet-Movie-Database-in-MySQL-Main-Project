#  Internet-Movie-Database-in-MySQL-Main-Project
It’s a massive online platform owned by Amazon that catalogs details about movies, TV shows, video games, and streaming content. It includes cast, crew, ratings, reviews, trivia, and more—helping users discover, rate, and explore entertainment worldwide.



##  MySQL Project: Internet Movie Database (IMDB) Analysis

###  Project Overview:
This project uses **MySQL** to explore and analyze a simulated IMDB-style movie database. It covers a wide range of SQL operations including aggregation, filtering, joins, subqueries, and window functions to extract meaningful insights from movie, rating, actor, and production data.



###  Key Tasks & SQL Challenges Covered:

#### 🔹 Data Profiling & Quality Checks
- Count total records in each table  
- Identify columns with null values in the `movie` and `names` tables  
- Find min/max values for each column in the `ratings` table (excluding `movie_id`)  

#### 🔹 Temporal Analysis
- Count movies released per year and analyze month-wise trends  
- Filter movies released between specific dates (e.g., April 2018–April 2019)  
- Analyze movies released in March 2017 in the USA with >1000 votes  

#### 🔹 Genre & Production Insights
- List unique genres and count movies with only one genre  
- Identify the genre with the highest number of movies  
- Find movies starting with “The” and having average rating > 8  
- Top 3 production companies by total votes  
- Most common production language  

#### 🔹 Actor & Director Analysis
- Actors/actresses in >3 movies with average rating < 5  
- Top 2 actors with median rating ≥ 8  
- Directors who worked on >3 movies  
- Average height of actors vs actresses  

#### 🔹 Ratings & Popularity
- Top 10 movies by average rating  
- Group movies by median rating  
- Total votes for movies released in 2018  
- Top 5 movies with highest total votes  

#### 🔹 Country & Comparison Queries
- Movies produced in USA or India in 2019  
- Compare average votes for German vs Italian movies  

#### 🔹 Historical & Duration-Based Queries
- 10 oldest movies with title, country, and director  
- Movie with longest duration, including genre and production company  



###  Tools & Technologies:
- MySQL: Querying and analysis  
- SQL Functions: COUNT, AVG, MIN, MAX, GROUP BY, HAVING, JOIN, CASE, DATE functions  
- Database Schema: Movies, Ratings, Names, Production, Genre, Country



###  Outcome:
This project demonstrates your ability to write complex SQL queries for real-world business and entertainment data. It highlights your skills in data exploration, trend analysis, and performance benchmarking — essential for roles in data analytics and business intelligence.

