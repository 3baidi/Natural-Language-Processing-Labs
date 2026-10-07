# Lab 3: N-Grams and Maximum Likelihood Estimation

## Overview
This folder contains the solution for NLP Lab 3. The objective was to build and evaluate a Maximum Likelihood Estimation (MLE) language model using N-grams (Bi-grams) to process and analyze a dataset of tweets.

## Tasks Completed
1. **Data Pre-processing:** Loaded a dataset of random tweets and cleaned the text by stripping out retweets (RTs), mentions, hashtags, URLs, and emojis using standard regular expressions.
2. **Model Training:** Tokenized the cleaned dataset and trained a Bi-gram MLE language model using the `nltk.lm` module.
3. **Evaluation:** Utilized the trained model to calculate specific bigram probabilities (e.g., $P(is \vert{} pakistan)$) and measured model uncertainty by calculating the perplexity of specific word sequences.

## Technologies Used
* `pandas` for data manipulation
* `nltk` for tokenization and N-gram MLE modeling
* `emoji` and `re` for text sanitization