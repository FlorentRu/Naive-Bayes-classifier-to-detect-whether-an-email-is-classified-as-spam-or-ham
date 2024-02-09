# Naive-Bayes-classifier-to-detect-whether-an-email-is-classified-as-spam-or-ham

Naive Bayes Email Spam Classification

Overview

This repository contains Python code for a Naive Bayes classifier designed to predict whether an email is spam or not spam. The classifier is trained on a dataset of emails, which can be downloaded using the provided download_corpus function. The dataset includes both ham (non-spam) and spam emails.

The code uses the CountVectorizer from scikit-learn for feature extraction and the MultinomialNB (Multinomial Naive Bayes) classifier for training. The performance of the classifier is evaluated using metrics such as accuracy, precision, recall, and F1 score.

This will download the email corpus, process the emails, train the Naive Bayes classifier, and evaluate its performance.

File Structure
naive_bayes_spam_classifier.py: The main Python script containing the Naive Bayes classifier code.
data/: Directory to store downloaded emails and the dataset.
downloads/: Directory to store downloaded email corpus files.
ham/: Directory to store non-spam (ham) emails.
spam/: Directory to store spam emails.
Customization
You can customize the dataset download and directories by modifying the download_corpus function and the directory paths in the script.
