# Sentiment Analysis of Movie Reviews using Naive Bayes

Overview

This project aims to perform sentiment analysis on movie reviews, classifying them as positive or negative using a Naive Bayes classifier. Sentiment analysis helps in understanding audience reception, recommending movies based on user preferences, and identifying trends in public opinion.
Dataset

The dataset consists of 1000 positive and 1000 negative movie reviews sourced from Cornell's movie review data.
Approach

    Data Acquisition: Load the data into a DataFrame.
    Data Preprocessing: Clean the review text by removing punctuation, stop words, and converting all words to lowercase. Tokenize and stem the words.
    Frequency Distribution Analysis: Analyze the dataset to identify the most frequent words in positive and negative reviews.
    Naive Bayes Model Training: Construct a term-document matrix and train a Naive Bayes classifier.
    Model Evaluation: Test the model on unseen reviews and evaluate its performance using metrics like accuracy, precision, recall, and F1-score.

Results

The model's performance can be evaluated using metrics like accuracy, precision, recall, and F1-score. These metrics help in understanding the effectiveness of the classifier in distinguishing between positive and negative reviews.
