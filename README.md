# Twitter Sentiment Analysis

This project aims to perform sentiment analysis on Twitter posts using machine learning models. The dataset contains tweets related to various brands and games, classified into four sentiment categories: **Positive**, **Negative**, **Neutral**, and **Irrelevant**. The project processes the data, builds a model, and evaluates its performance.

## Project Overview

- **Dataset**: The `twitter_training.csv` file contains the tweet text and its corresponding sentiment label.
- **Feature Extraction**: Features are extracted from tweet text using `CountVectorizer`.
- **Modeling**: Various classification algorithms (Naive Bayes, Random Forest, Decision Tree) are used to train the models.
- **Model Evaluation**: The performance of the models is evaluated using accuracy, classification reports, and confusion matrices.

## Requirements

This project requires the following Python libraries:

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `sklearn`
- `nltk`
- `wordcloud`

You can install these dependencies by running:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn nltk wordcloud

