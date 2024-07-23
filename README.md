# Emotion Detection in Tweets

This project involves classifying tweets to determine if they contain emotions directed at a brand or product. The classification is performed using machine learning models.

## Overview

The code performs the following steps:
1. **Data Loading**: Reads tweet data from a CSV file.
2. **Text Preprocessing**: Extracts tweet text and the corresponding target labels.
3. **Feature Extraction**: Converts text data into numerical features using `CountVectorizer`.
4. **Model Training**: Trains a `Multinomial Naive Bayes` classifier on a subset of the data.
5. **Model Evaluation**: Evaluates the model's performance on both training and validation sets.

## Prerequisites

Make sure you have the following Python packages installed:
- `pandas`
- `numpy`
- `scikit-learn`

## Results

- **Training Accuracy**: 0.8073
- **Validation Accuracy**: 0.6640

## Usage

1. Place your dataset file (`tweets.csv`) in the same directory as this script.
2. Run the script to train the model and evaluate its performance.
