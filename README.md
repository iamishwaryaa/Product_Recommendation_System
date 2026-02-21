# Product Recommendation System for E-Commerce

Built as part of a Social Network Analysis (SNA) Project

---

## Overview
This project implements a machine learning–based product recommendation system designed to simulate real-world e-commerce personalization. It combines multiple recommendation strategies to generate relevant suggestions across different business scenarios, including new users, returning customers, and newly launched platforms with no historical data.

The system consists of three core components:

**1. Popularity-Based Recommendation System**  
Identifies trending and most frequently purchased products and recommends them to new or anonymous users who have no prior interaction history.

**2. Collaborative Filtering Recommendation System**  
Uses user purchase history and ratings to generate recommendations. A matrix utility table is constructed and dimensionality reduction is applied using Truncated SVD. Product similarity is computed using correlation analysis to recommend similar items.

**3. Cold-Start Recommendation System**  
Designed for newly launched e-commerce platforms with no rating data. Uses product descriptions and natural language processing techniques to cluster products and recommend similar items based on textual similarity.

The models were tested on large-scale datasets containing:
- 2M+ user ratings
- 120K+ product descriptions

---

## Tech Stack & Libraries Used

**Language**
- Python

**Libraries**
- NumPy — numerical operations
- Pandas — data manipulation and preprocessing
- Matplotlib — visualization
- Scikit-learn — machine learning models and algorithms

**Machine Learning Techniques**
- Truncated SVD
- Correlation Similarity Matrix
- TF-IDF Vectorization
- K-Means Clustering
- Unsupervised Learning

---

## Impact & Usefulness
This project demonstrates how hybrid recommendation systems can address multiple real-world business challenges:

- Provides personalized recommendations using behavioral data
- Improves product discovery for new users
- Handles sparse data scenarios effectively
- Solves cold-start problems for new platforms
- Demonstrates scalable recommendation logic using large datasets
- Simulates production-level recommender system architecture

By integrating popularity-based, collaborative filtering, and content-based approaches, the system ensures accurate recommendations regardless of user history or data availability.

