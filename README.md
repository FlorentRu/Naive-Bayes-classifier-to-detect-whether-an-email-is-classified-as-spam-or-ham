# Naive-Bayes-classifier-to-detect-whether-an-email-is-classified-as-spam-or-ham

Naive Bayes Email Spam Classification

Overview

This repository contains Python code for a Naive Bayes classifier designed to predict whether an email is spam or not spam. The classifier is trained on a dataset of emails. The dataset includes both ham (non-spam) and spam emails.

The code uses the CountVectorizer from scikit-learn for feature extraction and the MultinomialNB (Multinomial Naive Bayes) classifier for training. The performance of the classifier is evaluated using metrics such as accuracy, precision, recall, and F1 score.

This codes can process the emails, train the Naive Bayes classifier, and evaluate its performance.

The main Python script containing the Naive Bayes classifier code.

ham/: Directory to store non-spam (ham) emails.

spam/: Directory to store spam emails.
