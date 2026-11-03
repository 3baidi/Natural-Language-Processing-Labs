# Lab 10: Introduction to Machine Translation (MT)

This repository contains the implementation for Lab 10 on Neural Machine Translation (NMT) using TensorFlow and Keras.

## Overview

The lab covers the theoretical foundations and practical implementation of sequence-to-sequence translation models:

- **Task 1: Model Architecture & Layer Concepts** – Answers key conceptual questions regarding the roles of the Embedding layer, Encoder LSTM, Decoder LSTM, and Softmax activation in NMT models.
- **Task 2: English-to-French Translation System** – Implements an end-to-end Neural Machine Translation pipeline:
  - Data preprocessing, tokenization, and sequence padding.
  - Encoder-Decoder LSTM architecture with `RepeatVector` and `TimeDistributed` Dense layers.
  - Model training, evaluation, and inference for translating English sentences to French.

## Requirements

- Python 3.10+
- `tensorflow`
- `pandas`
- `numpy`
- `scikit-learn`

## Installation

```bash
pip install tensorflow pandas numpy scikit-learn