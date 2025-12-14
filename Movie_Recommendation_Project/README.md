# Movie Recommendation System Using Content-Based Filtering
This project implements a content-based movie recommendation system using text similarity techniques. It recommends movies similar to a user’s favorite movie based on genres, keywords, tagline, cast, and director information.

## What the code does
* Loads movie dataset
* Selects important text-based features
* Handles missing values
* Combines multiple features into a single text representation
* Converts text data into numerical vectors using TF-IDF
* Calculates similarity between movies using cosine similarity
* Takes a movie name from the user
* Finds the closest matching movie title
* Recommends similar movies based on similarity scores

## Steps in the project
1. Import required libraries
2. Load the movie dataset
3. Check dataset shape (rows and columns)
4. Select relevant features for recommendation
5. Replace missing values with empty strings
6. Combine selected features into a single text column
7. Convert combined text data into TF-IDF feature vectors
8. Compute cosine similarity between all movies
9. Take favorite movie name as input from the user
10. Create a list of all movie titles
11. Find the closest matching movie title
12. Get the index of the selected movie
13. Calculate similarity scores for the selected movie
14. Sort movies based on similarity score
15. Display top recommended movies

## Result
* The system suggests a list of movies similar to the user’s favorite movie
* Recommendations are based on content similarity, not user ratings

## How to run
* Make sure the dataset file (movies.csv) is available
* Install required libraries (numpy, pandas, scikit-learn)
* Run the script in Python / Jupyter Notebook / Google Colab
* Enter your favorite movie name when prompted
