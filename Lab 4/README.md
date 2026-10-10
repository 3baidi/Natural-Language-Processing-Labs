# Lab 4: Text Classification and Evaluation in NLP

## Overview
This folder contains the solution for NLP Lab 4. The objective was to build and evaluate a text classification model to perform sentiment analysis on a dataset of Amazon Unlocked Mobile Phone reviews.

## Tasks Completed
1. **Data Pre-processing:** Loaded the dataset using `kagglehub` and applied five NLP preprocessing steps: lowercasing, special character removal, tokenization, stopword removal, and lemmatization.
2. **Data Splitting:** Divided the dataset into an 80/20 train-test split.
3. **Feature Extraction:** Converted the cleaned text into numerical features using a TF-IDF Vectorizer (capped at 5,000 features).
4. **Model Training:** Trained a Multinomial Naive Bayes classifier on the vectorized text.
5. **Evaluation:** Evaluated model performance using accuracy scores, a detailed classification report, and a plotted Confusion Matrix.

## Technologies Used
* `pandas` for data manipulation
* `nltk` for text preprocessing
* `scikit-learn` for TF-IDF extraction, Naive Bayes modeling, and metrics
* `matplotlib` for confusion matrix visualization