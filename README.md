# Fake News Detection System

## Overview
This project implements a fake news detection system using Natural Language Processing (NLP) and machine learning. It classifies news articles as "Real" or "Fake" using three models: Naive Bayes, Random Forest, and Passive Aggressive Classifier.

## Features
- Text preprocessing (lowercasing, tokenization, stopword removal)
- TF-IDF vectorization with n-grams
- Three trained models for comparison
- Confusion matrix visualization
- Custom input testing

## Requirements
- Python 3
- Libraries: `nltk`, `pandas`, `scikit-learn`, `seaborn`, `matplotlib`

## Usage
1. Place `True.csv` and `Fake.csv` in the working directory
2. Run the Jupyter notebook `app.ipynb`
3. The system will:
   - Preprocess the data
   - Train and evaluate models
   - Show accuracy metrics and confusion matrices
   - Test sample inputs
