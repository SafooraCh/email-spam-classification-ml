# Email Spam Classification Using Machine Learning

## Project Overview

This project implements an advanced Email Spam Classification system using Machine Learning and Natural Language Processing (NLP) techniques. The model classifies messages as **Spam** or **Ham (Not Spam)** using multiple machine learning algorithms and performance evaluation metrics.

The project was developed as part of a Machine Learning / Data Science internship project.

---

# Features

- Text preprocessing and cleaning
- Feature engineering
- TF-IDF vectorization
- Multiple machine learning models
- Cross-validation
- ROC-AUC evaluation
- Confusion matrix generation
- Model comparison and selection

---

# Dataset

Dataset Used:
SMS Spam Collection Dataset

Source:
Kaggle

Dataset Link:
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Regular Expressions (re)

---

# Machine Learning Models Used

1. Multinomial Naive Bayes
2. Logistic Regression
3. Linear Support Vector Machine (SVM)
4. Random Forest Classifier

---

# Project Workflow

Dataset Loading
        ↓
Text Preprocessing
        ↓
Feature Engineering
        ↓
TF-IDF Vectorization
        ↓
Train/Test Split
        ↓
Model Training
        ↓
Performance Evaluation
        ↓
Visualization

---

# Text Preprocessing

The following preprocessing steps were applied:

- Convert text to lowercase
- Remove punctuation
- Replace URLs with URL token
- Replace phone numbers with PHONE token
- Replace numeric values with NUM token
- Remove extra spaces

---

# Feature Engineering

Additional engineered features include:

- Message Length
- Word Count
- Uppercase Letter Ratio
- Exclamation Mark Count
- Frequency of the word "free"

---

# TF-IDF Configuration

- Unigrams and Bigrams
- Maximum Features = 5000
- English Stop Words Removal
- Minimum Document Frequency = 2

---

# Model Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- F1 Score
- ROC-AUC Score
- Cross Validation
- Confusion Matrix

---

# Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
