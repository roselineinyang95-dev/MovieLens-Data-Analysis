# MovieLens-Data-Analysis

## Project Overview
This project focuses on Data Cleaning, exploratory analysis, and performing feature engineering on the MovieLens dataset using Python.
The analysis examines movie ratings, genres, release years, and user-generated tags to uncover patterns that could support a future movie recommendation system.

## Objectives
Clean and prepare the MovieLens datasets,
Merge movie ratings with metadata and tags,
Perform feature engineering,
Explore rating patterns,
Identify meaningful insights,
Determine how the findings could support a recommendation system.

## Dataset: MovieLens Dataset
The dataset is a small portion of the MovieLens dataset, a collection of movie ratings and metadata collected by the GroupLens Research Group. It contains information on movie ratings, movie titles and genres, user-generated tags, and links to external movie databases. 
The datasets were cleaned and prepared by checking for missing values, duplicates, and data inconsistencies. The relevant tables were then merged using movieId to create a dataset for analysis. Additional features were engineered before conducting exploratory data analysis(EDA) to identify patterns and generate insights from the data. 

## Tools Used
-Python
-Pandas
-Numpy
-Matplotlib
-Seaborn
-Jupyter Notebook

## Feature Engineering
The following features were created
-Release Year
-Number of Genres
-Rating Year
-Rating Month
-Number of Ratings
-Movie Age at Rating
-Most Common Movie Tag

## Key Inisghts
1.	Most movies are rated between 3.0 and 4.5 stars. This indicates positive ratings.
2.	Drama, comedy, and action are the most common genres. Drama is the most frequent.
3.	The highest number of genres per movie is 3 
4.	The most common movie tags are ‘In Netflix queue’, ‘Atmospheric’, and ‘Superhero’.
5.	Movies with more tags usually have more user engagement.
6.	There was a steady rise in movie releases; as of 2000, this shows growing activity.

## Recommendation System Relevance
The engineered features can potentially support a future recommendation system by providing information about movie popularity, genre diversity, movie age, user ratings, and user-generated tags.
The Rating trends inform time-trend suggestions
























