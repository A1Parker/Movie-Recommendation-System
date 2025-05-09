# Movie-Recommendation-System
Built end to end movie recommendation system using NLP


# 🎬 Movie Recommendation System using NLP

A content-based movie recommender system that suggests similar movies based on textual metadata like genres, cast, crew, keywords, and overview. Built using Python, NLP techniques, and cosine similarity.

## 📌 Project Overview

This project leverages Natural Language Processing (NLP) and feature engineering to build a scalable recommendation engine. By combining key movie attributes into a unified text feature, the model calculates similarity between movies and returns the top 10 recommendations based on user input.

---

## 📂 Dataset

- **Source**: [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- **Files used**:  
  - `tmdb_5000_movies.csv`  
  - `tmdb_5000_credits.csv`

---

## 🧠 Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn** (CountVectorizer, Cosine Similarity)
- **NLP** (text cleaning, stopword removal, lemmatization)
- **Matplotlib**, **Seaborn**

---

## 🚀 Features

- Combines multiple metadata fields (overview, keywords, cast, crew, genres) into a single `tags` feature.
- Uses CountVectorizer for feature extraction and cosine similarity to find related movies.
- Recommends top 10 similar movies for a given movie title.
- Solves cold-start problem without requiring user ratings or interactions.
- Optimized for performance using vectorized operations and lightweight NLP techniques.

---
