# Recommender-System-For-Online-Ed-Platform
This project aims to enhance learners' experience by helping them quickly discover new courses of interest and improve their learning paths. Increased interaction through the recommender systems may also boost company revenue. The focus is on exploring and comparing machine learning models to identify the best-performing one in offline evaluations.

The project focuses on several key areas, including collecting and analyzing data from online course enrollment datasets and performing exploratory data analysis. It involves extracting Bag of Words (BoW) features from course content and calculating course similarity based on these features. The project also aims to develop content-based recommender systems using unsupervised learning techniques such as distance/similarity measurements, K-means, and Principal Component Analysis (PCA). Additionally, collaborative-filtering recommender systems will be built using supervised learning algorithms like K-Nearest Neighbors, Non-negative Matrix Factorization (NMF), Neural Networks, Linear Regression, Logistic Regression, and Random Forest.

## Table of Contents
1. [Exploratory Data Analysis on Online Course Enrollment Data](#exploratory-data-analysis-on-online-course-enrollment-data)
    - Identify keywords in course titles using a WordCloud
    - Calculate the summary statistics and visualizations of the online course content dataset
    - Determine popular course genres
    - Calculate the summary statistics and create visualizations of the online course enrollment dataset
    - Identify courses with the greatest number of enrolled students
2. [Extract Bag of Words (BoW) Features from Course Textual Content](#extract-bag-of-words-bow-features-from-course-textual-content)
    - Extract Bag of Words (BoW) features from course titles and descriptions
    - Build a course BoW dataset to be used for building a content-based recommender system later
3. [Calculate Course Similarity using BoW Features](#calculate-course-similarity-using-bow-features)
    - Calculate the similarity between any two courses using BoW feature vectors
4. [Classification-based Rating Mode Prediction using Embedding Features](#classification-based-rating-mode-prediction-using-embedding-features)
    - Build classification models to predict rating modes using the combined embedding vectors
5. [Clustering based Course Recommender System using K Nearest Neighbor](#clustering-based-course-recommender-system-using-k-nearest-neighbor)
    - Perform k-means clustering on the original user profile feature vectors
    - Apply PCA (Principal Component Analysis) on user profile feature vectors to reduce dimensions
    - Perform k-means clustering on the PCA transformed main components
    - Generate course recommendations based on other group members' enrollment history
6. [Collaborative Filtering Based Recommender System](#collaborative-filtering-based-recommender-system)
    - Perform KNN-based collaborative filtering on the user-item interaction matrix
7. [Collaborative Filtering based Recommender System using Non-negative Matrix Factorization](#collaborative-filtering-based-recommender-system-using-non-negative-matrix-factorization)
    - Perform NMF-based collaborative filtering on the user-item matrix
8. [Content-based Course Recommender System using Course Similarities](#content-based-course-recommender-system-using-course-similarities)
    - Obtain the similarity between courses from a course similarity matrix
    - Use the course similarity matrix to find and recommend new courses that are similar to enrolled courses
9. [Content-based Course Recommender System Using User Profile and Course Genres](#content-based-course-recommender-system-using-user-profile-and-course-genres)
    - Generate a user profile based on course genres and ratings
    - Generate course recommendations based on a user's profile and course genres
10. [Course Rating Prediction using Neural Networks](#course-rating-prediction-using-neural-networks)
    - Use `tensorflow` to train neural networks to extract the user and item latent features from the hidden layers
    - Predict course ratings with trained neural networks
11. [Regression-Based Rating Score Prediction Using Embedding Features](#regression-based-rating-score-prediction-using-embedding-features)
    - Build regression models to predict ratings using the combined embedding vectors

## Exploratory Data Analysis on Online Course Enrollment Data
- **Identify keywords in course titles using a WordCloud**: Analyzed course titles to identify prevalent keywords.
- **Calculate the summary statistics and visualizations of the online course content dataset**: Summarized and visualized content data.
- **Determine popular course genres**: Identified genres with the highest enrollment.
- **Calculate the summary statistics and create visualizations of the online course enrollment dataset**: Summarized enrollment data.
- **Identify courses with the greatest number of enrolled students**: Found courses with the highest student enrollments.

## Calculate Course Similarity using BoW Features
- **Calculate the similarity between any two courses using BoW feature vectors**: Compared courses based on their BoW representations.

## Classification-based Rating Mode Prediction using Embedding Features
- **Build classification models to predict rating modes using the combined embedding vectors**: Developed models to predict course rating modes.

## Clustering based Course Recommender System using K Nearest Neighbor
- **Perform k-means clustering on the original user profile feature vectors**: Clustered user profiles to identify patterns.
- **Apply PCA (Principal Component Analysis) on user profile feature vectors to reduce dimensions**: Reduced dimensionality for easier analysis.
- **Perform k-means clustering on the PCA transformed main components**: Clustering on transformed features for improved performance.
- **Generate course recommendations based on other group members' enrollment history**: Recommended courses based on peers' choices.

## Collaborative Filtering Based Recommender System
- **Perform KNN-based collaborative filtering on the user-item interaction matrix**: Implemented KNN to find similar user-item interactions.

## Collaborative Filtering based Recommender System using Non-negative Matrix Factorization
- **Perform NMF-based collaborative filtering on the user-item matrix**: Applied NMF techniques for collaborative filtering.

## Content-based Course Recommender System using Course Similarities
- **Obtain the similarity between courses from a course similarity matrix**: Generated a matrix to assess course similarities.
- **Use the course similarity matrix to find and recommend new courses that are similar to enrolled courses**: Provided recommendations based on course similarities.

## Content-based Course Recommender System Using User Profile and Course Genres
- **Generate a user profile based on course genres and ratings**: Created user profiles to tailor recommendations.
- **Generate course recommendations based on a user's profile and course genres**: Suggested courses based on individual user profiles.

## Course Rating Prediction using Neural Networks
- **Use `tensorflow` to train neural networks to extract the user and item latent features from the hidden layers**: Trained neural networks to identify latent features.
- **Predict course ratings with trained neural networks**: Generated predictions for course ratings.

## Extract Bag of Words (BoW) Features from Course Textual Content
- **Extract Bag of Words (BoW) features from course titles and descriptions**: Built BoW representations from course content.
- **Build a course BoW dataset to be used for building a content-based recommender system later**: Prepared dataset for future recommendations.

## Regression-Based Rating Score Prediction Using Embedding Features
- **Build regression models to predict ratings using the combined embedding vectors**: Developed regression models for rating predictions.

### Note
- Please refer to the multiple CSV files attached, as they will be utilized for the analyses.
