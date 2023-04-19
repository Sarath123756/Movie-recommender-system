# Movie-recommender-system
This is a simple movie recommender system that uses content-based filtering, NLTK vectorization, and cosine similarity to recommend movies based on the user's input.
# How it works
The system takes in the user's movie preferences as input and uses NLTK vectorization to extract features such as the summary,keywords, genre, and cast. The system then calculates the cosine similarity between the input movie and all the movies in the dataset.
Based on the cosine similarity scores, the system recommends the top 5 movies that are most similar to the user's input movie.
# Requirements
Python 3.x,
NLTK library,
Pandas library,
Scikit-learn library
# Limitations
This is a simple movie recommender system that uses content-based filtering, which means it only recommends movies based on the features of the movies in the dataset. It does not take into account the user's past behavior or preferences. Additionally, the system relies on NLTK vectorization and cosine similarity, which may not always accurately capture the similarity between movies.
# Dataset
The dataset was taken from kaggle.
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download
