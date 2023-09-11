# KAIBURR-TEXT-CLASSIFICATION-TASK-6

## Overview

This project focuses on text classification using the Consumer Complaint Dataset, aiming to categorize consumer complaints into different product categories. We have employed four different machine learning models for this task:

1. Multinomial Naive Bayes
2. Logistic Regression
3. Random Forest Classifier
4. Linear Support Vector Classifier (Linear SVC)

The goal of this project is to compare the performance of these models in accurately classifying consumer complaints and provide a clear understanding of the process.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites installed:

- Python (3.7 or higher)
- Jupyter Notebook (optional but recommended)

## Dataset

The Consumer Complaint Database is a collection of complaints about consumer financial products and services that we sent to companies for response. Complaints are published after the company responds, confirming a commercial relationship with the consumer, or after 15 days, whichever comes first. Complaints referred to other regulators, such as complaints about depository institutions with less than $10 billion in assets, are not published in the Consumer Complaint Database. The database generally updates daily.[https://catalog.data.gov/dataset/consumer-complaint-database]

## Models Used

### 1. Multinomial Naive Bayes

- Model Type: Multinomial Naive Bayes
- Description: This model is based on the Naive Bayes algorithm and is well-suited for text classification tasks.
- Performance: Accuracy - 53.55%

### 2. Logistic Regression

- Model Type: Logistic Regression
- Description: Logistic Regression is a linear classification algorithm known for its simplicity and interpretability.
- Performance: Accuracy - 61.30%

### 3. Random Forest Classifier

- Model Type: Random Forest Classifier
- Description: Random Forest is an ensemble learning method that combines multiple decision trees to make predictions.
- Performance: Accuracy - 60.30%

### 4. Linear Support Vector Classifier (Linear SVC)

- Model Type: Linear Support Vector Classifier
- Description: Linear SVC is a type of Support Vector Machine (SVM) designed for linearly separable data.
- Performance: Accuracy - 61.875%

## Usage

To run the project and evaluate the models, follow the instructions provided in the Jupyter Notebook files for each model. You can experiment with different preprocessing techniques, hyperparameter tuning, and feature engineering to improve model performance.
