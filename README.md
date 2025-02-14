# Research-Paper-Text-Classification
# Text Classification of Five Mental‐Health Categories

## Introduction

This project focuses on classifying research papers into five related categories in the domain of mental health research. The goal is to analyze the semantic differences between the categories and evaluate machine learning models for text classification.

## Datasets

The program requires five datasets, each corresponding to one of the mental health categories: Anxiety.csv, Depression.csv,PTSD.csv, OCD.csv, BipolarDisorder.csv

## How to run the program

### Step 1: Preprocessing

This step performs the following:

1. Loads the datasets.
2. Cleans and preprocesses text data.
3. Random seleclt a 100 words paragrapg from abstracts.
4. Saves the preprocessed dataset as prepared_dataset.csv.
5. Visualize Data

### Step 2: Feature engeering

This step is to transfer content into numerical features, methods like bag of words, TFIDF, n-grams are used. Split the data set into train and test data sets.

### Step 3: Train machine learning models

Trains multiple models, including: Naïve Bayes, SVM, Random Forest, K-Nearest Neighbor, SGD Classifier, XGBoost
**Note:** XGBoost took around 5 mins to run.

### Step 4: Evaluation

Use 10-fold cross validation to compare models' performance

### Step 5: Error analysis

Identifying misclassified samples, calculating the overall error rate.

### Step 6: Bias analysis

Examines potential biases in the dataset and model performance, including age-related bias, temporal bias.

# Environment properties

Before running the project, install dependencies. We utilizes the following Python libraries: pandas, numpy, nltk, matplotlib, wordcloud, torch, scikit-learn, transformers, xgboost, tqdm, seaborn, re, random

## How to run the project
