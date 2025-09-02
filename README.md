# Smart-Sentiment-Classifier-for-Product-Reviews

# Project Overview
This project focuses on analyzing customer product reviews to determine their sentiment (positive, negative, or neutral). By applying machine learning techniques to textual data, we aim to provide businesses with actionable insights from customer feedback.

The workflow involves data preprocessing, feature extraction using TF–IDF, model training, evaluation, and inference.

# Problem Statement
Online marketplaces generate vast amounts of customer feedback. Manually analyzing these reviews is inefficient.
The objective is to build a system that can automatically classify reviews into sentiment categories, enabling businesses to monitor customer satisfaction and improve services.

# Objectives
Load and clean raw product review data.

Convert text into numerical representations using TF–IDF.

Train multiple models: Logistic Regression, Linear SVM, and Random Forest.

Evaluate model performance using accuracy, F1-score, and confusion matrix.

Provide a ready-to-use predict_sentiment() function for quick predictions.

# Methodology

Dataset Preparation: Import product reviews from Product_Reviews.csv.

Text Cleaning: Lowercasing, removing punctuation, digits, and URLs.

Feature Engineering: TF–IDF vectorization with unigrams and bigrams.

Modeling: Train Logistic Regression, Linear SVM, and Random Forest.

Evaluation: Use accuracy, F1-score, and confusion matrix to compare models.

# Results

Best Model: Logistic Regression (in most cases)

Performance Metrics: Achieved strong accuracy and F1-scores across classes.

Key Insights: Simple linear models with TF–IDF features can effectively capture sentiment in product reviews.

Error Analysis: Inspect misclassified reviews to understand model weaknesses.

Deployment Helper: Implement predict_sentiment() for real-time predictions.
