# Churn-Prediction-System-Using-Python-Machine-Learning-and-NLP.

# Project Overview
In this project, the objective was to develop a system that automatically categorizes negative reviews into specific bad word categories based on their content. Here's a detailed summary of the technical steps and outcomes:

# Data Preparation and Exploration
Dataset Loading and Exploration: The dataset containing  and reviews their corresponding categories was loaded using Pandas. Initial exploration involved checking the shape of the dataset and visualizing the distribution of resume entries across different product categories using matplotlib and seaborn.

# Text Preprocessing
Cleaning: review text underwent extensive cleaning to ensure standardized text inputs for analysis. This involved removing URLs, special characters, punctuation, and emojis characters using regular expressions (regex).

# Sentiment Analysis
Performed Sentiment anaysis to separate the positive and negative reviews on the basis of their sentiment score.

# Feature Extraction
TF-IDF Vectorization: TF-IDF (Term Frequency-Inverse Document Frequency) vectorization was employed to convert cleaned text reviews into numerical feature vectors. This technique assigns weights to words based on their importance in individual reviews relative to the entire dataset, capturing unique content characteristics.

# Clustering 
Using KMeans Clustering to cluster the bad words from the negative reviews dataframe. 

# Model Training and Evaluation
Classifier Selection: A K-Nearest Neighbors (KNN) classifier was chosen for multi-class classification to predict bad words categories from the TF-IDF transformed features.

# Model Evaluation:
The trained classifier was evaluated using accuracy metrics on a test set to assess its performance in accurately categorizing the negative reviews for the churn prediction.

# Outcome
System Capabilities: Successfully developed a scalable system capable of automating the categorization of new reviews into negative review categories with high accuracy. This project demonstrates the practical application of natural language processing (NLP) and machine learning (ML) techniques in the domain of churn prediction analysis, facilitating more efficient and objective customer care practices.
