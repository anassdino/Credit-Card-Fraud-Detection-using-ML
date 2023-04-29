# Credit Card Fraud Detection with Logistic Regression

This project aims to detect credit card fraud using logistic regression. We explore different feature sets and apply the Synthetic Minority Over-sampling Technique (SMOTE) to address the class imbalance issue. The dataset used for this project is the "creditcard.csv" file.

## Installation Requirements

- Python 3.6+
- pandas
- numpy
- scikit-learn
- imbalanced-learn

You can install the required packages using `pip`:

```bash
pip install pandas numpy scikit-learn imbalanced-learn
```

## Usage

1. Place the "creditcard.csv" file in the same directory as the Python script.
2. Run the Python script. It will perform the following steps:
    - Load the dataset into a pandas DataFrame.
    - Split the dataset into training and testing sets.
    - Train a logistic regression classifier on the full feature set and evaluate its performance.
    - Apply SMOTE to the training set and retrain the classifier.
    - Compare the performance of the full feature set with and without SMOTE.
    - Identify the best features to retain and evaluate the performance of the reduced feature set.
    - Apply SMOTE to the reduced feature set and retrain the classifier.
    - Compare the performance of the full feature set with SMOTE and the reduced feature set with SMOTE.

## Overall Structure

The code is organized into the following sections:

- Importing necessary libraries
- Loading the dataset and performing basic data exploration
- Splitting the dataset into training and testing sets
- Training the logistic regression classifier on the full feature set
- Applying SMOTE to the training set
- Evaluating the performance of the full feature set with and without SMOTE
- Identifying the best features to retain
- Training the classifier on the reduced feature set
- Applying SMOTE to the reduced feature set
- Evaluating the performance of the reduced feature set with and without SMOTE
- Comparing the performance of the full feature set with SMOTE and the reduced feature set with SMOTE

After running the script, you will see the performance metrics of the different feature sets with and without SMOTE. This will help you determine the best approach for credit card fraud detection using logistic regression.
