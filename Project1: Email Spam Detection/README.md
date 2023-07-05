# 📧 Email Spam Detection

This project focuses on developing an email spam detection system using NLP techniques. The objective is to accurately classify emails as either spam or non-spam (ham) based on their content.

## Project Overview

The goal of this project is to build a machine learning model that can effectively identify and classify spam emails. The project involves the following steps:

1. Data Preprocessing: The email dataset is preprocessed by cleaning the text, removing stop words, and performing tokenization.

2. Feature Extraction: Textual data is transformed into numerical feature vectors using the TF-IDF (Term Frequency-Inverse Document Frequency) technique. This helps capture the importance of each word in the emails relative to the entire corpus.

3. Model Training: A logistic regression model is trained on the preprocessed and feature-extracted data. Logistic regression is a popular algorithm for binary classification tasks.

4. Model Evaluation: The trained model is evaluated using various metrics such as accuracy, precision, recall, and F1 score. These metrics provide insights into the model's performance and its ability to correctly classify spam and non-spam emails.

## 🗂️ Repository Structure

- `Email spam detection with Machine Learning.ipynb`: Jupyter Notebook containing the code, explanations, and visualizations for the email spam detection project.
- `spam.csv`: CSV file containing the email dataset used for training and testing the model.

## 📋 Requirements

To run the code and reproduce the results, you need the following dependencies:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

You can install the required libraries using pip:
pip install numpy pandas scikit-learn nltk matplotlib seaborn


Happy detecting! 🚫📧
