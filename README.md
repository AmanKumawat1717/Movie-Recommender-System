# Movie-Recommender-System

Introduction

Recommender systems have two main techniques: collaborative and content-based. Content-based recommender systems recommend based on data that the user likes.
This system recommends movies of your choice. I have not uploaded similarity.pkl and datasets which are used in this project due to its greater size. In project.ipynb entire code is written in jupyter notebook to recommend movies.

Data Description

We obtained the dataset from Kaggle.com (from this link) and it consists of 45K movies released on or before July 2017. There are 24 features such as budget, genres, overview, revenue, release dates, languages, production companies, TMDB vote counts and vote averages, etc. However, these are the features that we are focused on:

id: The ID of the movie in TMDB.
imdb_id: The ID of the movie in IMDB.
original_title: The name of the movie.
overview: The plot of the movie from TMDB.
genres: The genres of the movie.
In addition, we will use The Movie Database (TMDB) API to retrieve the keywords for each movie and we will scrape the plots of the movies from IMDB to increase our word count. Here are the additional features:

keywords: The keywords that describe the movie.
imdb_plot: The plot of the movie from IMDB

Tools

1. Python 
2. Pandas and Numpy for data manipulation.
3 .Sklearn for unsupervised learning.
4. NLTK for text manipulation.
5. Streamlit

