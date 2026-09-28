# SMS Spam Classifier

## Project Overview

This project uses supervised machine learning to classify SMS messages as **Spam** or **Ham** (normal message).

## Objective

The objective is to build and evaluate machine learning models for automatic SMS spam detection.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF

## Machine Learning Algorithms

Two classification algorithms were used:

1. Logistic Regression
2. Random Forest

## Data Preprocessing

The project includes:

- Missing-value checking
- Duplicate removal
- Label encoding
- Train/test split
- TF-IDF text feature extraction

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- 5-Fold Cross-Validation

## Visualizations

The notebook includes:

- Model comparison graph
- Logistic Regression confusion matrix
- Random Forest confusion matrix
- ROC curve comparison

## Project Structure

```text
spam-classifier/
│
├── Spam_Classifier.ipynb
└── README.md
