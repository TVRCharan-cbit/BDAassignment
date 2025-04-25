
# Project Summary: Machine Learning with Spark (Colab)

This project showcases three core machine learning models using **Apache Spark in Google Colab**, each built on synthetic yet realistic datasets.

## 1. Classification Model – Plant Survival Predictor

**Goal:** Predict whether a plant survives based on environmental conditions.

- **Algorithm:** Logistic Regression (and optionally Decision Tree)
- **Features:** Soil moisture, sunlight hours, temperature
- **Unique Twist:** Custom-built dataset for plant health classification
- **Output:** Survival prediction (0 = No, 1 = Yes)  
- **Tools:** `pyspark.ml.classification.LogisticRegression`

## 2. Clustering Model – Customer Spending Segmentation

**Goal:** Group customers based on monthly spending behavior.

- **Algorithm:** KMeans Clustering
- **Features:** Spending on food, electronics, and entertainment
- **Unique Twist:** Micro dataset simulating realistic spending patterns
- **Output:** Customer cluster assignments & cluster centers  
- **Tools:** `pyspark.ml.clustering.KMeans`

## 3. Recommendation Engine – Movie Recommender System

**Goal:** Recommend top movies to users based on past ratings.

- **Algorithm:** ALS (Alternating Least Squares)
- **Features:** User ID, Movie ID, Rating
- **Unique Twist:** Lightweight, synthetic rating data for easy demos
- **Output:** Top-N movie recommendations per user  
- **Tools:** `pyspark.ml.recommendation.ALS`
