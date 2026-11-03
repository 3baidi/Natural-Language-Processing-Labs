# Lab 8: Part-of-Speech (POS) Tagging

## Overview
This folder contains the solution for NLP Lab 8. The objective of this lab was to explore Part-of-Speech (POS) tagging using both NLTK and spaCy, examining coarse-grained vs. fine-grained tags and visualizing sentence dependency parses.

## Tasks Completed
1. **SpaCy POS Extraction:** Evaluated coarse-grained (`pos_`) and fine-grained (`tag_`) tags for specific tokens and generated explanations across a full sentence.
2. **Contextual POS Disambiguation:** Analyzed how spaCy dynamically shifts POS tags for polysemous words ("Google" as Proper Noun vs. Verb; "Table" as Noun vs. Verb) based on context.
3. **Dependency Visualization:** Used spaCy's `displacy` rendering engine to plot syntactic dependency trees and POS structures visually.

## Technologies Used
* `spacy` (`en_core_web_sm`) for statistical POS tagging and parsing
* `nltk` for tokenizer comparison and rule-based tagging
* `displacy` for dependency tree visualizations