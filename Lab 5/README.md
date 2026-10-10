# Lab 5: Text Representation

## Overview
This folder contains the solution for NLP Lab 5. The objective was to explore different techniques for text representation and embedding, specifically focusing on converting text into numerical vectors that machine learning models can process while capturing inter-word semantics.

## Tasks Completed
1. **Cosine Similarity:** Calculated the similarity between multiple text documents using the dot product of their vectors.
2. **TF-IDF Vectorization:** Applied Term Frequency-Inverse Document Frequency to identify and extract the most important words from a corpus.
3. **Word2Vec Training:** Preprocessed the Simpsons script lines dataset (lowercasing, punctuation removal, tokenization) and trained a Skip-gram Word2Vec model.
4. **Semantic Similarity:** Utilized the trained Word2Vec model to find words semantically similar to specific characters (e.g., Homer, Marge, Bart).
5. **Contextual Outliers:** Used the model's `doesnt_match` function to identify the odd word out within specific character groupings.

## Technologies Used
* `pandas` for dataset manipulation
* `nltk` for text preprocessing and tokenization
* `scikit-learn` for TF-IDF vectorization and Cosine Similarity calculations
* `gensim` for training and querying the Word2Vec model