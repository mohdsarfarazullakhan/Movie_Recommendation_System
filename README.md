🎬 Movie Recommendation System

A content-based movie recommendation system built using Python, Scikit-learn, and Streamlit.
The app recommends movies similar to the one selected by the user and displays movie posters fetched from TMDB API.

**Features**

Content-based movie recommendations

Uses cosine similarity

Interactive Streamlit web app

Displays movie posters using TMDB API

Fast and lightweight

Beginner-friendly project structure

**Tech Stack**

Python 3.10

Pandas & NumPy

Scikit-learn

Streamlit

Requests

Pickle

TMDB API

**How It Works**

Movie metadata is vectorized using CountVectorizer

Cosine similarity is calculated between movies

On user selection, the most similar movies are recommended

Posters are fetched dynamically from TMDB API

**TMDB API Key**

This project uses TMDB API to fetch movie posters.

You can get your own API key from:
 $$https://www.themoviedb.org/

**Example Output**

Select a movie from dropdown

Click Show Recommendation

Get 5 similar movies with posters
