# 🎬 Movie Recommendation System

This project is a basic **content-based movie recommendation system** built using Python and Jupyter Notebook. It suggests similar movies based on the text description ("overview") of a given movie using **cosine similarity**.

##  Features

- Recommends movies similar to the one you input
- Uses **TF-IDF vectorization** on movie overviews
- Computes similarity using **cosine similarity**
- Simple and easy to understand implementation
- Ideal for learning **NLP basics**, **text similarity**, and **recommender systems**

##  Technologies Used

- Python 
- Jupyter Notebook 
- Pandas
- Scikit-learn (TF-IDF, Cosine Similarity)
- Numpy

##  Dataset

The dataset used is a subset of [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) which contains metadata like movie titles, overviews, genres, cast, etc.

> Only the `title` and `overview` columns were used for this basic recommender.

##  How It Works

1. **TF-IDF Vectorization** is applied to the overview column to convert text into numerical format.
2. **Cosine similarity** is calculated between the vectors.
3. When a user inputs a movie name, the system returns the top N most similar movies based on description.

##  How to Use

1. Clone this repository or open the notebook in Jupyter.
2. Make sure to place the dataset (`movies.csv` or similar) in the same directory.
3. Run the notebook step-by-step.
4. Call `recommend('Movie Title')` to get suggestions.

