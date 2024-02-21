# SOEN 471 - TEAM 9 - Project Summary

## Introduction

This project aims to analyze a movie database along with different user reviews. This dataset contains metadata for 45,000 movies alongside 26 million ratings for all 45,000 movies. The main goal of this project is to build a movie recommendation system based on the ratings and votes of users found on the platform and to test different models for recommendation systems which are prominently used in today’s online media consumption.

## Dataset Description

[This dataset can be found on Kaggle.](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv)

The dataset comprised of 45,000 movies which were listed in the full MovieLens Dataset. The data consists of movies released before July 2017. This first dataset is built upon 24 different features as movie metadata: 
- Adult: Whether the movie is rated as an adult film or not (boolean) 
- Belongs_to_collection
- Budget: The budget of the film (int) 
- Genres: Genres of the movie (dict) 
- Homepage: Homepage link of the film (string) 
- Id: Unique identifier for the film (int) 
- Imdb_id: Unique IMDB ID (int) 
- Original_language: Original language of the movie (string) 
- Original_title: Movie title (string) 
- Overview: Short description of the film (string) 
- Popularity: Popularity scale from 0 to 30 (int) 
- Poster_path: Link to movie poster (string) 
- Production_companies: Names of the production companies involved (dict) 
- Production_countries: Countries involved in the production of the film (dict) 
- Release_date: Date of the release of the movie (date) 
- Revenue: Total revenue accrued from the movie (int) 
- Runtime: Total length of the film in minutes (double) 
- Spoken_languages: Language spoken by the characters of the movie (dict) 
- Status: Status of the movie, released, rumored, in production etc.. (string) 
- Tagline: Tagline of the movie (string) 
- Title: Title of the film (string) 
- Video 
- Vote_average: Average vote or rating given by viewers. (type: float)
- Vote_count: Total count of votes received for the movie. (type: int)

The second dataset is a large dataset which comprises over 26 million ratings for the movies in the previous dataset. For 270,000 users in total. The features for this dataset include: 
- Userid: Unique identifier for the user (int) 
- Movieid: ID of the movie being reviewed (int) 
- Rating: User rating on a scale of 0 to 5 (double) 
- Timestamp: Date of the rating (date) 

## Research Questions
The project aims to address the following research questions:
1. How to build a movie recommendation system using past user ratings?
2. Which movie feature would be the most optimal to increase the effectiveness of recommendations?
3. Which system model yields the most promising results?

## Model Design
### Class of Models
We plan to use recommender system models to recommend movies to different user profiles. The selected class of models includes:
- *Collaborative Filtering Model*: Recommends items based on user-item interactions and similarities between users or items.
- *Content-Based Filtering Model*: Recommends items similar to those that a user has liked or interacted with based on item attributes.

### Algorithms
The algorithms to be applied include:
- *Matrix Factorization*: Decomposes the user-item matrix to recommend movies based on user preferences.
- *Decision Trees*: Classifies and predicts user preferences based on movie attributes.

### Model Comparison
We will compare the performance of the algorithms using metrics such as accuracy, precision, recall, and F1-score. The comparison will provide insights into the strengths and weaknesses of each algorithm.

## Conclusion
The project summary outlines the objectives, dataset characteristics, research questions, and model design for analyzing The Movies Dataset found on Kaggle.
