# Movie-recommendations
This project implements a movie recommendation system using Python, leveraging both content-based and collaborative filtering techniques. The system uses a dataset containing information about movies and TV shows from Netflix. Visualizations are included to help understand the distribution of genres and the performance of recommendations.
# Features
Content-Based Filtering: Recommends movies based on the similarity of content features such as cast, director, genre, and description.
Collaborative Filtering: Provides recommendations based on user-item interaction patterns. Note: In this example, we use a dummy interaction matrix for demonstration.
Visualizations: Includes visualizations of:
Top recommendations with similarity scores.
User-item interaction matrix heatmap.
Distribution of movie genres.
# Requirements
Python 3.x
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
# Data
The dataset used is a CSV file containing information about Netflix movies and TV shows. The columns include:

show_id
type
title
director
cast
country
date_added
release_year
rating
duration
listed_in
description
