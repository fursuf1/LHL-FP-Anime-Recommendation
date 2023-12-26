# Anime Recommendation System

Welcome to our Anime Recommendation System project!

This repository contains notebooks, scripts, and data related to our anime recommendation system. The goal is to develop an efficient recommendation system to suggest anime titles to users based on their preferences and behavior.
# Table of Contents

## [Overview](#overview) 🌟
Introduction to the project, its goals, and components.

## [Techniques Used](#techniques-used) 🔧
Explanation of the methodologies, tools, and libraries utilized in the project.
- [Exploratory Data Analysis (EDA)](#eda) 📊
- [Machine Learning algorithms with TensorFlow](#tensorflow) 🤖
- [WordCloud visualization](#wordcloud) ☁️
- [Language Detection using langdetect](#langdetect) 🌐

## [Instructions](#instructions) 📝
Guidance on running notebooks and scripts, checking dependencies, and exploring the project components.

## [Dataset Source](#dataset-source) 📂
Information about the origin of the datasets used in the project (Kaggle).

## [Exploratory Data Analysis (EDA) Graphs](#eda-graphs) 📈
Detailed list and description of the graphs generated in Notebook 1, showcasing various insights extracted from the anime dataset.

## [Model Training with Deep Learning](#deep-learning) 🧠
Explanation of the techniques employed in training the recommendation models, including 3D visualization of ratings graphs and collaborative filtering.

## [Bokeh Plotting for Model Metrics](#bokeh-plotting) 📊
Usage of Bokeh for interactive visualization of model metrics (loss, MSE, MAE) against epochs during training.

## [Item-Based Recommendation Section](#item-recommendation) 📚
Description and implementation of item-based recommendation techniques for suggesting similar anime titles.

## [User-Based Recommendation](#user-recommendation) 🤝
Explanation and implementation of user-based recommendation approaches, analyzing user behavior to suggest relevant anime titles.

## [Model Training: Content-Based Filtering (CBF) and Recommendations](#content-based-filtering) 🔍
Details about employing Content-Based Filtering for model training based on anime features and generating recommendations.

## Overview

This repository consists of two main notebooks:

- **[Notebook 1: Exploratory Data Analysis (EDA) and Dataset Overview](link_to_notebook1)**:
  This notebook focuses on comprehensive data exploration and analysis of the anime datasets. Through visualizations and insights, it delves into the distribution of anime titles, genres, user ratings, and other pertinent features.

- **[Notebook 2: Model Training](link_to_notebook2)**:
  Notebook 2 deals with training the anime recommendation model. It involves implementing various machine learning algorithms using TensorFlow, such as collaborative filtering, content-based filtering, or hybrid models.

## Techniques Used

The anime recommendation system leverages the following techniques:

- **Exploratory Data Analysis (EDA)**: Understanding the distribution, relationships, and patterns within the anime datasets using Pandas, Matplotlib, Seaborn, and Plotly for visualization.
- **Machine Learning algorithms**: Utilizing TensorFlow framework for recommendation system development, employing techniques such as collaborative filtering, content-based filtering, or hybrid models.
- **WordCloud**: Employed for visualizing text data within anime titles, synopsis, and other textual information, providing a graphical representation of word frequency.
- **Language Detection (langdetect)**: Utilizing langdetect library to detect the primary language in 'Other name' fields, aiding in language-specific analysis or processing.

### TensorFlow

[TensorFlow](https://www.tensorflow.org/) is an open-source machine learning framework developed by Google. It's widely used for building and training machine learning models, particularly in the domain of neural networks. For our anime recommendation system, TensorFlow facilitates the creation and training of recommendation models, allowing for the development of advanced algorithms like collaborative filtering or deep learning-based models.

### WordCloud

[WordCloud](https://github.com/amueller/word_cloud) is a data visualization technique used to represent text data, emphasizing the frequency of words through their size in a visual cloud. In our project, WordCloud was employed to visually showcase word frequency within anime titles, synopsis, or other textual information from the dataset, aiding in the identification of prominent terms or phrases.

### langdetect

[Langdetect](https://pypi.org/project/langdetect/) is a language detection library in Python that identifies the primary language of a given text. In our project, langdetect was utilized to detect and classify the primary language from the 'Other name' fields in the anime dataset. This information aids in language-specific analysis, potentially enabling language-based recommendations or insights for multilingual users.

## Instructions

- The notebooks and scripts in this repository provide detailed steps and code to analyze the anime dataset and train the recommendation system.
- Before running the notebooks, ensure all necessary dependencies are installed. Refer to the `requirements.txt` file for the required libraries and their versions.
- Detailed explanations, visualizations, and code implementations are provided in the notebooks.

Feel free to explore the notebooks and scripts for a detailed understanding of our anime recommendation system.

## Dataset Source

The datasets used in this project have been obtained from [Kaggle](https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset).

## Exploratory Data Analysis (EDA) Graphs

The EDA in Notebook 1 generated various insightful graphs:

- Count of Anime Titles by Type
- Top 15 Most Popular Animes
- Anime Score vs. Number of Scores
- Top 15 Animes by Number of Users
- Count of Anime Titles by Genre
- Top 20 Most Popular Genres In The Anime Industry
- Distribution of Anime Genres
- Word Embedding Plot - Genre
- Distribution of Anime Popularity by Type
- Distribution of Anime Scores by Type
- Relationship between Popularity, Number of Scores, and Score
- Relationship between Popularity, Scored By, and Score
- Correlation Matrix
- Top 10 Anime Licensors
- Distribution of Premiered Seasons
- Number of Animes Premiered by Year
- Number of Animes by Studio (Top 10)
- Number of Animes by Source
- Top 10 Most Favorited Anime
- Top 10 Most Favorited Anime (Treemap)
- Distribution of Anime Ratings
- Count of Animes based on its Native Name
- Gender Distribution
- Age Distribution
- Top 20 User Locations by count
- Top 15 Users Based by Metrics
- Watching Behavior of X
- Top 10 Anime Titles Watched by Most Users

## Model Training with Deep Learning

### 3D Visualization of Ratings Graphs

The 3D Visualization of Ratings Graphs was employed to understand the interaction between user ratings and anime features in a multidimensional space. It helps in visualizing the relationship and patterns within the data for better model comprehension.

### Model Training (Collaborative Filtering)

The collaborative filtering technique was implemented for model training. It involves predicting user preferences for anime titles based on similar users' preferences. This method explores user-item interactions and recommends anime based on user behavior.

### Bokeh Plotting for Model Metrics

Bokeh Plotting was utilized for visualizing model loss, Mean Squared Error (MSE), and Mean Absolute Error (MAE) against epochs in inverted bar graphs. This plotting technique offers interactive visualizations, enabling a detailed view of model performance throughout the training process.

### Item-Based Recommendation Section

The item-based recommendation approach was used to suggest anime titles based on similarities between items. It identifies similar anime titles and recommends them to users who have interacted with comparable items in the past.

### User-Based Recommendation

The user-based recommendation technique analyzes user behavior and preferences to recommend anime titles to similar users. It identifies users with similar tastes and suggests anime based on their interactions and preferences.

### Model Training: Content-Based Filtering (CBF) and Recommendations

Content-Based Filtering (CBF) was employed for model training, focusing on anime features such as genre, type, duration, and more. This technique generates recommendations based on the content similarities between anime titles and user preferences.

