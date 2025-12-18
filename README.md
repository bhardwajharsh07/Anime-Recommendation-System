# Anime-Recommendation-System
## Problem Statement

With thousands of anime titles available across multiple genres and formats, users often struggle to find content that matches their interests. Manual searching is time-consuming and inefficient. This project aims to build a content-based recommendation system that suggests similar anime based on their characteristics.

## Dataset

The dataset consists of anime-related metadata, including:
* Anime titles
* Genre
* Type (TV, Movie, OVA, etc.)
* Episodes
* Rating (1-10)
* Members (popularity metric)
Before modeling, the data was cleaned and preprocessed to handle missing values and convert categorical features into numerical representations suitable for machine learning.

## Approach

Applied **data preprocessing** and **feature vectorization** to represent anime metadata numerically.
Implemented a **K-Nearest Neighbors (KNN)** algorithm with **cosine similarity** to measure similarity between anime feature vectors.
Built a **recommendation funtion** that takes an **anime title** and **number of titles** as input and returns the **top-N most similar anime**, ensuring modular and reusable code.

## Outcome

Successfully generated top-N (if N is not provided, it is taken as 5 by default) relevant anime recommendations in under one second from a dataset containing thousands of records.
Reduced manual search effort and improved content discovery through accurate, similarity-based recommendations.
