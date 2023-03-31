# CA05 - kNN based Movie Recommender Engine
Overview
This project involves building a movie recommender system using the k-Nearest Neighbors (kNN) algorithm in Python. The recommender system takes a movie's features as input and returns the top 5 most similar movies based on genre and IMDB rating.

Dataset
The dataset used in this project is a subset of data extracted from the UCI's IMDB dataset. It contains 30 movies with data for each movie across seven genres and their IMDB ratings. The dataset can be found here.

Requirements
Python 3.x
pandas
scikit-learn
Implementation
The implementation uses the scikit-learn library to create a kNN model. It involves the following steps:

Import the necessary libraries (pandas and scikit-learn).
Load the dataset from the provided URL.
Preprocess the data by removing unnecessary columns and extracting movie titles.
Create a kNN model using the scikit-learn library.
Prepare a feature vector for the given movie ("The Post") and input it into the model.
Display the top 5 most similar movies based on the input movie's features.
Usage
To use the movie recommender system, follow these steps:

Clone this repository or download the Python script.
Install the required libraries using pip install pandas scikit-learn.
Run the script in a Python environment or Jupyter Notebook.
The output will display the top 5 most similar movies to "The Post" based on the given feature vector.
