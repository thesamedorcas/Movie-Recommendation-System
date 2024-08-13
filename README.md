# Movie Recommendation System

This project implements a content-based movie recommendation system using Python. It suggests movies similar to a user's input based on features such as genres, keywords, taglines, cast, and director.

## Features

- Uses cosine similarity to find movies with similar content
- Processes a dataset of over 4800 movies
- Provides up to 30 movie recommendations based on user input

## Dependencies

- numpy
- pandas
- scikit-learn
- difflib

## How it works

1. The system loads movie data from a CSV file.
2. It processes the data, combining relevant features into a single text string for each movie.
3. The text data is converted into numerical data using TF-IDF vectorization.
4. Cosine similarity is calculated between all movies based on their feature vectors.
5. When a user inputs a movie title, the system finds the closest match in its database.
6. It then returns a list of movies most similar to the input, based on the cosine similarity scores.

