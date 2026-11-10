# Lab 12: Transformers and Self-Attention


## Overview

The lab explores sequence processing, tokenization, embeddings, and self-attention mechanisms in Transformer models:

- **DistilBERT Sentiment Analysis** – Loads a fine-tuned `distilbert-base-uncased-finetuned-sst-2-english` model, tokenizes text, inspects layer geometries, and evaluates sequence classification outputs.
- **Self-Attention Mechanics** – Extracts and analyzes attention matrices from Transformer layers.
- **BERT Model Inspection Task** – Evaluates `bert-base-uncased`:
  - Inspects layer count ($12$), attention heads per layer ($12$), and total heads ($144$).
  - Tokenizes input sequences and extracts target attention weights from specific layers and heads.
  - Explains the mathematical representation of rows and columns in self-attention probability matrices.

## Requirements

- Python 3.10+
- `transformers`
- `torch`
- `matplotlib`

## Installation

```bash
pip install transformers torch matplotlib