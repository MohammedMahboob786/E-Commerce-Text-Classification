
---
# E-commerce Text Classification

This repository contains a Python script for text classification in an e-commerce context. The script includes data preprocessing, balancing the dataset, training and evaluating classification models, and using FastText for text classification.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Data Preprocessing](#data-preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Text Classification with FastText](#text-classification-with-fasttext)

## Introduction

The goal of this project is to perform text classification in the e-commerce domain. The script covers data preprocessing, text classification model training, and evaluation.

## Data

The dataset used in this project is 'ecommerceDataset.csv.' It contains information about different e-commerce product categories and their descriptions. The dataset is preprocessed to handle missing values and standardize category names.

## Data Preprocessing

Data preprocessing steps include:
- Handling missing values
- Standardizing category names
- Combining 'category' and 'desc' columns
- Subsampling the data to balance categories
- Text preprocessing (removing special characters, extra spaces, and converting text to lowercase)

## Model Training and Evaluation

The script trains and evaluates two classification models:
1. **Logistic Regression:** A supervised classification model trained on preprocessed text data.
2. **Gradient Boosting Classifier:** Another supervised classification model for text classification.
   
The models are evaluated on training and testing datasets, and accuracy and classification reports are provided.

## Text Classification with FastText

The script utilizes FastText, a library for efficient text classification. It trains a text classification model using the 'cat_desc' column and evaluates its performance.

Feel free to explore the code and use it for your own e-commerce text classification tasks.

---