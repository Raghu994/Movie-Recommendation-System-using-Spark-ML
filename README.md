Movie Recommendation System using PySpark ALS

Overview
This project demonstrates a movie recommendation system built using the MovieLens dataset and PySpark’s ALS (Alternating Least Squares) algorithm.
The system predicts movies that users are likely to enjoy but haven’t rated yet.

Dataset:
MovieLens Small Dataset (ml-latest-small)

Contains:
ratings.csv: user ratings of movies
movies.csv: movie titles and genres

Features
Data cleaning and preprocessing (casting columns, handling missing values)
Merging movies and ratings tables
Train/test split (80/20)
Collaborative filtering using ALS
UC-safe top-N recommendations per user
Final output shows userId, top recommended movies, genres, and predicted ratings

Steps
Load and explore the data using PySpark.
Merge ratings and movies tables.
Clean the data (drop unnecessary columns, cast types for ALS).
Split data into train and test sets.
Train ALS model.
Predict ratings for unrated movies.
Generate top-N recommendations per user (UC-safe).
Join with movie titles and genres for readable output.
