# Lab 7: Large Language Models (LLMs)

## Overview
This folder contains the solution for NLP Lab 7. The objective was to explore the three main Transformer model families (Encoder-only, Encoder-decoder, and Decoder-only) and apply them to specific natural language processing tasks using the Hugging Face `transformers` library.

## Tasks Completed
1. **Model Architecture Selection:** Categorized various NLP tasks (sentiment analysis, translation, summarization, etc.) into their appropriate Transformer architectures.
2. **Encoder-Only Application:** Utilized a pre-trained DistilBERT model via the `pipeline` API to perform sentiment classification on a set of sentences.
3. **Encoder-Decoder Application:** Implemented `google/flan-t5-small` using `AutoTokenizer` and `AutoModelForSeq2SeqLM` to summarize a paragraph about transformer mechanics.
4. **Architecture Analysis:** Analyzed and explained the structural advantages of Decoder-only models (like GPT) for autoregressive text generation in conversational AI applications.

## Technologies Used
* `transformers` (Hugging Face) for accessing pre-trained LLMs
* `torch` (PyTorch) as the underlying deep learning backend
* `pipeline`, `AutoTokenizer`, and `AutoModelForSeq2SeqLM` for model execution