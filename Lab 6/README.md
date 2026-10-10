# Lab 6: Deep Learning for NLP

## Overview
This folder contains the solution for NLP Lab 6. The objective was to build and evaluate deep learning models using PyTorch to perform binary sentiment classification (positive/negative) on a dataset of Yelp restaurant reviews.

## Tasks Completed
1. **Data Preprocessing & Splitting:** Cleaned the Yelp reviews (lowercasing, punctuation removal) and split the data into 80/20 train-test sets.
2. **TF-IDF Neural Network:** Converted text to numerical vectors using TF-IDF and trained a simple PyTorch neural network (Input -> 64 -> 32 -> Output) using `BCEWithLogitsLoss` and the Adam optimizer.
3. **Word2Vec Representation (Task 1):** Tokenized the reviews and trained a Word2Vec model (Skip-gram, vector size 200) to create continuous word embeddings, converting sentences to mean vectors.
4. **Deep Neural Network with Word2Vec (Task 2):** Built and trained a deeper PyTorch neural network (Input -> 128 -> 64 -> 32 -> Output) utilizing the Word2Vec embeddings to classify review sentiment.

## Technologies Used
* `torch` (PyTorch) for building and training the neural networks
* `pandas` for dataset loading and manipulation
* `gensim` for training Word2Vec embeddings
* `nltk` for text tokenization
* `scikit-learn` for TF-IDF vectorization and performance metrics