# Real-vs-Fake_News_Classifier

This project is focused on building a machine learning model to classify news articles as real or fake. The primary goal is to explore text preprocessing techniques, vectorization, and classification methods for textual data.

# Introduction

The Real vs Fake News Classifier project aims to tackle the challenge of detecting misleading or fake news articles using machine learning techniques. This project includes:

1) Preprocessing textual data (removing special characters, stemming, stopword removal).
2) Vectorizing text using TF-IDF.
3) Training a classifier using Logistic Regression.
4) Evaluating performance with accuracy and classification metrics.

# Dataset
The dataset used for this project is from Kaggle's Fake News competition:https://www.kaggle.com/c/fake-news/data?select=train.csv

# Description:
1) title: The headline of the article.
2) text: The main content of the article.
3) author: The author of the article.
4) label: The target variable where:
  # 0 = Fake News
  # 1 = Real News

# Features
1) Text Preprocessing: Cleaning and stemming text for better model performance.
2) Vectorization: TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert text into numerical format.
3) Classification: Logistic Regression is employed as the classification algorithm.

# Results
Accuracy: Achieved  95.43%  accuracy on the test set.
