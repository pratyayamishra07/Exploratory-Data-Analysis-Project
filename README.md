# Exploratory-Data-Analysis-Project
Netflix Originals: Exploratory Data Analysis (EDA)
Project Overview
This project provides an exploratory data analysis (EDA) of Netflix Originals using MySQL. The objective is to uncover trends, patterns, and insights from the dataset, which includes information about titles, genres, IMDB scores, languages, and runtime.
The analysis involves cleaning the data, performing descriptive statistics, and extracting actionable insights. The results can help understand the characteristics of Netflix content, its genre trends, and other key aspects.

Dataset
The dataset used for this analysis contains the following columns:
Title: Name of the Netflix show or movie.
Genre: Genre of the content (e.g., Documentary, Thriller).
Premiere: Premiere date of the content.
Runtime: Duration of the content in minutes.
IMDB Score: IMDb rating of the content.
Language: Language(s) of the content.
The dataset includes 584 entries and was pre-processed before loading into the MySQL database.

Objectives
Perform data cleaning to handle missing or duplicate entries.
Explore the dataset to understand:
Content distribution across genres and languages.
Yearly trends in content releases.
Average IMDb scores and runtime by genre.
Identify top-rated content.
Export cleaned data for visualization in tools like Tableau or Power BI.

Steps in Analysis
1. Database and Table Setup
Created a MySQL database named NetflixEDA.
Defined the schema for the NetflixOriginals table and imported the dataset.
2. Data Cleaning
Checked for missing and null values.
Removed rows with missing critical data like Title or Genre.
3. Data Exploration
Performed key analyses, including:
Total count of Netflix Originals.
Distribution of content by genre and language.
Average IMDb scores and runtime across genres.
4. Advanced Analysis
Identified top 10 highest-rated shows/movies.
Analyzed trends in yearly content releases.
Explored the relationship between genre and runtime.
5. Data Export
Cleaned data and analysis results exported for visualization in .csv format.


Results
Top Genres: Genres like Documentaries and Thrillers dominate the Netflix Originals catalog.
Yearly Trends: A steady increase in content production over the years, with peak releases in recent years.
Top-Rated Content: Identified titles with the highest IMDb ratings, showcasing diverse genres.
Runtime Insights: Documentaries tend to have shorter runtimes, while Science Fiction has higher averages.

Future Work
Perform sentiment analysis on user reviews (if data is available).
Expand the dataset to include non-Netflix originals for comparative analysis.
Develop machine learning models to predict IMDb scores based on available features.
