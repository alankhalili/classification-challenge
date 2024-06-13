# classification-challenge
# Module 13
# Spam Detector

## Overview

This project involves creating a spam detector using machine learning techniques. The dataset used for this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/94/spambase). The goal is to classify emails as spam or not spam based on various word and character frequency features.

## Dataset

The dataset contains 58 columns, including word and character frequency features, capital run length features, and a 'spam' label indicating whether the message is spam (1) or not (0).

### Example of Dataset Columns:
- `word_freq_make`: Frequency of the word 'make'
- `word_freq_address`: Frequency of the word 'address'
- `word_freq_all`: Frequency of the word 'all'
- `char_freq_$`: Frequency of the character '$'
- `capital_run_length_average`: Average length of uninterrupted sequences of capital letters
- `capital_run_length_longest`: Length of the longest uninterrupted sequence of capital letters
- `capital_run_length_total`: Total number of capital letters in the email
- `spam`: Label indicating whether the email is spam (1) or not (0)

## Jupyter Notebook

The Jupyter notebook `spam_detector.ipynb` contains the following sections:

1. **Import Libraries**: Import necessary libraries such as `pandas`, `sklearn`, etc.
2. **Retrieve the Data**: Load the dataset using Pandas and display the first few rows to confirm the import.
3. **Predict Model Performance**: Make predictions about which model (Logistic Regression or Random Forests Classifier) will perform better.
4. **Data Preprocessing**: Perform data cleaning, encoding, and feature selection.
5. **Model Training**: Train Logistic Regression and Random Forests models on the preprocessed data.
6. **Model Evaluation**: Evaluate the models using metrics such as accuracy, precision, recall, etc.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- Dataset Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/94/spambase)
-