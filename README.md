# Sentiment Classification of Tweets using Machine Learning

This project focuses on analyzing the sentiment of tweets using Machine Learning techniques and the TF-IDF vectorization method. The goal is to classify tweets into categories such as Positive, Negative, Neutral, and Irrelevant, and visualize the overall sentiment distribution.

<img width="1363" height="822" alt="Screenshot 2025-08-27 094135" src="https://github.com/user-attachments/assets/7e4abc6a-6d1b-40fa-aeb5-c0d9b7ca901a" />

<img width="1329" height="590" alt="output" src="https://github.com/user-attachments/assets/cfce4193-c490-4aa6-bce9-724647b7600c" />

🚀 Project Workflow

Data Preprocessing

Tweets were cleaned by removing stopwords, punctuation, numbers, and URLs.

Text normalization (lowercasing, tokenization, etc.) was applied.

Feature Extraction (TF-IDF)

Used TF-IDF (Term Frequency – Inverse Document Frequency) to convert text into numerical vectors.

Helps highlight important words in tweets while reducing the weight of commonly used words.

Model Training

Machine Learning model trained on TF-IDF features.

Model learns to classify tweets into sentiment classes.

Evaluation

Achieved ~72% accuracy.

Metrics (Precision, Recall, F1-Score) were also evaluated.

User Input Prediction

A simple input system allows users to test custom tweets and get predictions.
