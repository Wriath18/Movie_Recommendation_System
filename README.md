# Simple Content-Based Movie Recommendation System

## Introduction
This project implements a simple content-based movie recommendation system using the MovieLens 100K dataset (`ml-100k`). It aims to recommend movies to users based on their past ratings and the content characteristics of the movies.

## Dataset
We use the MovieLens 100K dataset, which comprises 100,000 ratings from 943 users on 1682 movies. It is a widely adopted dataset in the recommender system community and includes user ratings, movie metadata, and demographic information.

## Recommendation Technique
Our system employs content-based filtering, which makes recommendations by comparing the rating of movies. When a user rates a movie, the system suggests similar movies based on the user ratings other similar users have provided.

## Implementation Details
- **Data Preprocessing**: The data was cleaned and transformed to create a user-item matrix.
- **Feature Extraction**: We engineered features from the movie metadata to represent each movie's content.
- **Similarity Computation**: Cosine similarity was used to find the similarity between movies.
- **Rating Predictions**: The system predicts potential ratings for movies that a user has not yet watched.
- **Recommendation Generation**: Movies are ranked according to the predicted ratings, and the top recommendations are provided to the user.

## Usage
Users can interact with the system by providing their user ID from the dataset. The system will generate movie recommendations based on their historical ratings.

## Libraries Used
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotplib`
- `seaborn` 

## Results
The system successfully generates a list of 5 movie recommendations tailored to the user's preferences, focusing on thematic and genre alignment.



## Contributing
Contributions to this project are welcome. Please fork the repo, make your changes, and submit a pull request for review.

## License
This project is open-sourced under the MIT License. See the LICENSE file for more information.
