# SMS Spam Classifier

## Project Overview

This project uses supervised machine learning to classify SMS messages as either **Spam** or **Ham**.

## Objective

The objective is to build and evaluate machine learning models that can automatically identify unwanted spam messages.

## Dataset

The project uses the SMS Spam Collection dataset.

Each message belongs to one of two classes:

- Ham — normal message
- Spam — unwanted message

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Machine Learning Algorithms

Two classification algorithms were compared:

1. Logistic Regression
2. Random Forest

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Removed duplicate records
- Converted labels into numerical values
- Converted text into numerical features using TF-IDF

## Train/Test Split

The dataset was divided into:

- 80% training data
- 20% testing data

## Cross-Validation

Five-fold cross-validation was performed to evaluate model consistency.

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

Additional visualizations include:

- Confusion matrices
- ROC curve
- Model performance comparison

## Project Files

- `Spam_Classifier.ipynb` — Complete machine learning notebook
- `model_results.csv` — Model comparison results

## Conclusion

This project demonstrates how supervised machine learning can be used to automatically classify SMS messages as Spam or Ham. Logistic Regression and Random Forest were trained and evaluated using multiple performance metrics.
