# CBTC


Email Spam Detector with Machine Learning

Overview
This GitHub repository contains the source code for an email spam detector built using Python and machine learning. The project utilizes a dataset with labeled examples to classify emails into spam and non-spam categories.

Features
Built with Python and scikit-learn.
Implements a Naive Bayes classifier for spam detection.
Utilizes CountVectorizer for feature extraction from email text.

Dataset
The dataset (spam.csv) includes two columns:

v1: Labels (ham or spam)
v2: Email text


Results
Accuracy: 0.9838565022421525
Confusion Matrix:
[[963   2]
 [ 16 134]]
Classification Report:
              precision    recall  f1-score   support

         ham       0.98      1.00      0.99       965
        spam       0.99      0.89      0.94       150

    accuracy                           0.98      1115
   macro avg       0.98      0.95      0.96      1115
weighted avg       0.98      0.98      0.98      1115
