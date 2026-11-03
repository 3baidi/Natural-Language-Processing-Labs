# Lab 9: Named Entity Recognition (NER) using spaCy

This repository contains the implementation for Lab 9 on Named Entity Recognition (NER) using Python and spaCy.

## Overview

The lab covers entity extraction, visualization, and custom model training across three tasks:

- **Task 1: Interactive Entity Extraction** – Accepts user input sentences, processes them using spaCy's `en_core_web_sm` pipeline, and prints detected entities with their labels and descriptions.
- **Task 2: Visualization & Structured Data** – Renders named entities using `spacy.displacy` and extracts entity metadata into a structured Pandas DataFrame.
- **Task 3: Custom NER Model Training** – Builds a blank English NLP pipeline, trains a custom NER component on character-aligned annotations for 20 iterations, saves the trained model to disk (`custom_ner_model`), and reloads it for prediction testing.

## Requirements

- Python 3.10+
- `spacy`
- `pandas`
- Pre-trained model: `en_core_web_sm`

## Installation

```bash
pip install -U spacy pandas
python -m spacy download en_core_web_sm