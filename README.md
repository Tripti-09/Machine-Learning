# Machine-Learning

# Credit Card Fraud Detection

This repository contains code and resources for credit card fraud detection using machine learning techniques. The objective of this project is to develop a robust model that can accurately identify fraudulent credit card transactions, thus aiding in fraud detection and prevention.

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Credit card fraud is a significant concern in the financial industry, and detecting fraudulent transactions is crucial for minimizing financial losses and ensuring customer trust. This project aims to leverage machine learning algorithms to build a predictive model that can identify fraudulent credit card transactions accurately.

We compare the performance of different machine learning algorithms, including logistic regression, decision tree, random forest, neural network, and support vector machine, on a test dataset. By evaluating their accuracy and other relevant metrics, we determine the most effective algorithm for credit card fraud detection.

## Data

The dataset used in this project is a collection of credit card transactions, labeled as either fraudulent or non-fraudulent. The dataset can be obtained from [this Kaggle link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It is an imbalanced dataset, meaning that the number of fraudulent transactions is significantly lower than the number of non-fraudulent transactions. Handling imbalanced data is an essential aspect of credit card fraud detection, and appropriate techniques such as oversampling, undersampling, or synthetic data generation can be employed to address this issue.

## Usage

To use this project, follow these steps:

1. Download the credit card fraud dataset from [this Kaggle link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
2. Preprocess the data, including handling missing values, normalizing features, and addressing the class imbalance using suitable techniques.
3. Train and evaluate the machine learning algorithms included in the codebase. Modify the code as needed for your specific dataset and requirements.
4. Analyze the results to determine the algorithm with the highest accuracy and best performance for credit card fraud detection.

## Results

The results of the algorithm comparison on the imbalanced dataset are as follows:

- Logistic Regression: 93.91% accuracy on the test data
- Decision Tree: 93.91% accuracy on the test data
- Random Forest: 90.86% accuracy on the test data
- Neural Network: 77.66% accuracy on the test data
- Support Vector Machine: 89.85% accuracy on the test data

Based on these results, both logistic regression and decision tree algorithms demonstrate the highest accuracy for credit card fraud detection on the imbalanced dataset.

## Contributing

Contributions to this project are welcome. If you have suggestions, improvements, or new ideas, please feel free to submit a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE). You are free to modify, distribute, and use the code and resources as permitted by the license.
