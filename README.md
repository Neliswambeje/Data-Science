# Sentiment Analysis Notebook

## Overview

This notebook includes a baseline TF-IDF + Logistic Regression sentiment classifier and instructions to swap in a transformer model for fine-tuning.

## Notebook Contents

1. Load IMDB or custom review CSV
2. Preprocess text and split data
3. Vectorize with TF-IDF
4. Train Logistic Regression baseline
5. Evaluate performance and test sample inference

## How to run

* Place `imdb_reviews.csv` (columns: review, sentiment) if available.
* To use transformers, install `transformers` and prepare tokenized datasets.

## Presentation notes

* Explain trade-offs: baseline is fast and interpretable, transformers perform better at scale.

