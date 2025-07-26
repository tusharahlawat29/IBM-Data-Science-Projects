# 🎬 Project 11: Movie Recommendation System

## 📌 Overview
This project builds a **content-based movie recommender system** using the TMDB 5000 Movie dataset. It applies **natural language processing (NLP)** to extract key features like genres, keywords, and overview, and then computes **cosine similarity** to recommend similar movies.

---

## 📂 Dataset
- **Name**: TMDB 5000 Movies Dataset  
- **Source**: [Kaggle Dataset Link](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)  
- **File Used**: `tmdb_5000_movies.csv`

---

## 🎯 Objectives
- Combine multiple features into a unified content tag  
- Vectorize the text using **CountVectorizer**  
- Compute similarity using **cosine similarity**  
- Recommend top 5 most similar movies

---

## 🧰 Tools & Libraries Used
- Python  
- Pandas  
- Scikit-learn  
- NLP (CountVectorizer)  
- Cosine Similarity (from `sklearn.metrics.pairwise`)

---

## ⚙️ How It Works
1. Select features like `overview`, `genres`, and `keywords`
2. Clean and merge into a new column: `tags`
3. Vectorize the `tags` using **CountVectorizer**
4. Compute **cosine similarity** between movie vectors
5. Recommend movies based on user input title

---

## ✅ Sample Output

**Input**: `Avatar`  
**Top 5 Recommendations**:
- John Carter  
- Guardians of the Galaxy  
- Ender's Game  
- Pirates of the Caribbean  
- The Last Airbender

---

## 📌 Conclusion
This project introduces the basics of **Content-Based Recommendation Systems**, which are widely used in platforms like **Netflix**, **Amazon**, and **IMDb**. It’s a great foundation to build more advanced systems like:
- Collaborative Filtering
- TF-IDF Based Recommendations
- Deep Learning-Based Recommenders

