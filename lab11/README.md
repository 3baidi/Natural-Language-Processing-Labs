# Lab 11: Attention Mechanism with Recurrent Neural Networks (RNN)

This repository contains the implementation for Lab 11 on the Attention Mechanism using PyTorch, TensorFlow/Keras, and Pandas.

## Overview

The lab explores how attention mechanisms allow neural networks to dynamically focus on key words when processing sequential input for Question-Answering (Q&A) classification:

- **Preprocessing & Setup** – Lowercases input questions, tokenizes text, pads sequences to uniform length, and converts datasets to PyTorch tensors.
- **Model Architecture** – Implements a PyTorch `nn.Module` consisting of:
  - `nn.Embedding` for dense word vector representations.
  - `nn.RNN` to process sequential token embeddings.
  - `nn.Linear` attention layer that computes normalized softmax weights per word.
  - Final classification layer mapping weighted context vectors to target answer groups.
- **Task 1: Attention Weight Visualization** – Plots attention distributions across multiple dataset questions, confirming that key content words receive higher attention weights than generic functional words.
- **Task 2: Comparative Attention Analysis** – Evaluates attention weight behavior on semantically similar questions with different phrasing, demonstrating how attention highlights central semantic predicates.

## Requirements

- Python 3.10+
- `torch`
- `tensorflow`
- `pandas`
- `matplotlib`

## Installation

```bash
pip install torch tensorflow pandas matplotlib