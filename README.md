# TEXT CLASSIFICATION USING CONSUMER COMPLAINT DATASET

## Overview

Welcome to the Text Classification Task! This project showcases the power of text classification using the Consumer Complaint Dataset. Our primary aim is to categorize consumer complaints into distinct product categories. To accomplish this, we've harnessed the capabilities of four cutting-edge machine learning models.

## Dataset

Our dataset originates from the Consumer Complaint Database, a repository of complaints about consumer financial products and services. These complaints are submitted to companies for responses and become public after the company's confirmation or after 15 days, whichever comes first. The dataset updates regularly, ensuring we work with the most current data. [Source](https://catalog.data.gov/dataset/consumer-complaint-database)

## Getting Started

### Prerequisites

Before diving into this exciting project, ensure you have the following prerequisites in place:

- **Python** (version 3.7 or higher)
- **Jupyter Notebook** (optional but highly recommended)

## Data Preprocessing

Before feeding the data into our machine learning models, we conducted thorough data preprocessing to prepare the text for analysis. These preprocessing steps ensure that the text data is in a suitable format for training and evaluation.

### Text Cleaning

We initiated the data preprocessing by cleaning the text. The following steps were performed:

1. **Lowercasing**: All text was converted to lowercase to ensure uniformity in text data.

2. **Special Character Removal**: We removed special characters, symbols, and numerical digits from the text, retaining only alphabetic characters.

3. **Tokenization**: The text was tokenized into words, breaking down the sentences into individual words or tokens.

### Stopword Removal

Stopwords, such as "and," "the," and "in," were removed from the text. These common words don't carry substantial meaning and can be excluded to improve model efficiency.

### Feature Engineering

To enhance the performance of our models, we conducted feature engineering. This involved:

1. **TF-IDF Vectorization**: We used TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert the text data into numerical format. This method assigns weights to words based on their importance in each document relative to the entire dataset.

2. **Max Features Selection**: To manage computational resources effectively, we limited the maximum number of features to control the dimensionality of the data.
These data preprocessing steps played a crucial role in optimizing our text classification models' performance.


### Classifiers Used:

1. **Multinomial Naive Bayes**
   - Model Type: Multinomial Naive Bayes
   - Description: Leveraging the Naive Bayes algorithm, this model excels in text classification.
   - Performance: Achieved an accuracy of 68.42%.

2. **Logistic Regression**
   - Model Type: Logistic Regression
   - Description: Known for its simplicity and interpretability, Logistic Regression is a powerful linear classification algorithm.
   - Performance: Impressive accuracy of 79.70%.

3. **Random Forest Classifier**
   - Model Type: Random Forest Classifier
   - Description: Harnessing the strength of ensemble learning, this model combines multiple decision trees for predictions.
   - Performance: Delivered an accuracy rate of 75.92%.

4. **Linear Support Vector Classifier (Linear SVC)**
   - Model Type: Linear Support Vector Classifier
   - Description: Tailored for linearly separable data, Linear SVC is a robust Support Vector Machine variant.
   - Performance: Stood out with a remarkable accuracy of 79.85%.

## Conclusion

- In the world of text classification, model selection is not a one-size-fits-all proposition. While Linear SVC stood out with the highest accuracy, it's important to remember that the choice of the best model depends on the specific needs and goals of our text classification task. Factors like model interpretability, training time, and scalability must also be weighed in the decision-making process.

- We've gone beyond accuracy to scrutinize precision, recall, and F1-score, providing a more comprehensive performance evaluation. This holistic approach proves crucial when dealing with imbalanced datasets or when certain classes carry greater significance.

- Furthermore, we've highlighted the immense potential for optimization through hyperparameter tuning and feature engineering. By experimenting with different configurations and data preprocessing techniques, we can unlock the full capabilities of each model.
