# Amazon Reviews Sentiment Analysis
## Project Overview

This project implements Natural Language Processing (NLP) techniques to classify Amazon product reviews into positive and negative sentiments. Both traditional machine learning models (Naïve Bayes, Logistic Regression) and deep learning models (RNN, LSTM) are used to compare performance and evaluate model effectiveness.

The goal is to demonstrate how NLP can be applied for sentiment analysis in e-commerce, helping businesses understand customer opinions, improve products, and detect potential fraud.
## Key Features

Preprocessing Pipeline:

Lowercasing, punctuation removal, tokenization, and stop-word removal

Handles informal language (emojis, slang) and ensures clean text for model input

Data Balancing:

Oversampling applied to handle class imbalance between positive and negative reviews

Traditional Machine Learning Models:

Naïve Bayes (with and without TF-IDF)

Logistic Regression (with and without TF-IDF)

Deep Learning Models:

RNN (with and without TF-IDF)

LSTM (with and without TF-IDF)

Includes embedding layers, sequence padding, and early stopping for training efficiency
## Model 
Traditional Machine Learning

Naïve Bayes: Efficient and simple; performs well for large, sparse datasets

Logistic Regression: Strong baseline for binary classification; works well with TF-IDF

Deep Learning

RNN: Captures sequential dependencies; limited in learning long-range context

LSTM: Captures long-term dependencies; best overall performance in sentiment classification

Training Steps:

Text tokenization and encoding

Padding sequences for uniform length

Splitting data into training and testing sets

Model building, compilation (Adam optimizer, binary crossentropy loss)

Early stopping to prevent overfitting

Evaluation using precision, recall, F1-score, and confusion matrix
## Findings
LSTM models outperform RNN and traditional machine learning models in handling long-term dependencies in text data.
## References

Liddy, E. D., 2001. Natural language processing.

Murthy, G. S. N., et al., 2020. Text-based sentiment analysis using LSTM. IJERT, 9(05).

Ruales, J., 2011. Recurrent neural networks for sentiment analysis. IEEE.

Mikolov, T., et al., 2010. RNN based language model. Interspeech.

Wang, X., et al., 2015. Predicting tweet polarities using LSTM. ACL.

Liao, S., et al., 2017. CNN for sentiment analysis of Twitter data. Procedia Computer Science, 111, 376–381.

Evaluation Metrics:

Precision, Recall, F1-score, Confusion Matrix, and Test Accuracy
