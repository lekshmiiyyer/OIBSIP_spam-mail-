# OIBSIP_spam-mail-
3 Introduction
Spam emails are unsolicited and often malicious emails that flood users' inboxes. This project aims to build a spam email detector using machine learning algorithms. It preprocesses text data, trains a model using a dataset of labeled emails, and deploys a web interface for users to classify emails as spam or non-spam.

# Features
Web Application: Flask-based frontend for users to input email text and receive classification results.
Machine Learning Model: Trained using a dataset of labeled spam and non-spam emails.
Preprocessing: Text data preprocessing includes removing stopwords, tokenization, and TF-IDF vectorization.
Evaluation: Model performance metrics include accuracy(0.96), precision, recall, and F1-score.
# Usage
Enter email text into the provided text area.
Click on the "Predict" button to classify the email as spam or non-spam.
# Model Training
The model is trained using the Multinomial Naive Bayes classifier on a dataset of labeled emails.
Training includes text preprocessing (removing punctuation, stopwords, and vectorization using TF-IDF).
3 Files Included
mail.py: Flask web application for email classification.
spam_detector_model.pkl: Trained model saved using joblib.
tfidf_vectorizer.pkl: TF-IDF vectorizer for text preprocessing.
templates/index.html: HTML template for the frontend.
# Technologies Used
Python
Flask
scikit-learn (sklearn)
HTML/CSS
