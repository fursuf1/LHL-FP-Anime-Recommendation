# LHL-FP-Anime-Recommendation

# Anime Recommendation System

Welcome to our Anime Recommendation System project!

This repository contains notebooks, scripts, and data related to our anime recommendation system. The goal is to develop an efficient recommendation system to suggest anime titles to users based on their preferences and behavior.

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
