# Authorship-Profiling

## About
This project builds classification algorithms that predicts the gender of the author based on their tweets. The dataset contains:
1. `train labels.csv` contains training ids and gender. It contains twitter posts from 3,100 authors and acts as the training data.
2. `test_labels.csv` contains 500 testing ids and gender.
3. `Data.zip` contains 3,600 twitter texts for those authors, which acts as the training and testing data.

## Data Preparation and Extraction
We have done lowercasing, stopwords removal and cleaning, tokenization, stemming, and lemmatization.
## Feature Extraction
TF-IDF has been used for feature extraction.
## Model Building
Many classification models has been tried and we got SVM with better accuracy.
