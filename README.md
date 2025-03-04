# Text Based Emotion Classification System

## Aim:
The primary aim of an emotion classification project is to develop a system capable of accurately identifying and categorizing human emotions from various input modalities.



<!DOCTYPE html>
<html>
<head>
</head>
<body>
  <h1>Welcome</h1>
  <p>Here's an image:</p>
  <img src="https://github.com/mayurdhoble/Emotion-classification-/blob/master/output_of_emotion_classifier.png?raw=true" alt="A picture of a project">
</body>
</html>


## Libraries used:

1) Pandas: For data manipulation and analysis.

2) NumPy: For numerical operations.

3) NeatText: For text cleaning and preprocessing.

4) Scikit-learn: For machine learning models, vectorization, and evaluation metrics.

5) Streamlit : To create beautiful User Interfce.

## Preprocessing:

# NeatText: Used to clean and preprocess text data. It removes unwanted characters, numbers, and special characters.

Text is converted to lowercase.

Stop words are removed.

Tokenization is performed.

## Feature Extraction:

## CountVectorizer: Converts text data into numerical feature vectors. It creates a vocabulary of words and counts their occurrences in each document.

## Model:

Logistic Regression: A multi-class classification model is used to predict the emotion based on the text features.
The model is trained on the preprocessed text data and corresponding emotion labels.

## Emotion Classes:

The model classifies text into eight emotion classes: 'anger', 'disgust', 'fear', 'joy', 'neutral', 'sadness', 'shame', 'surprise'.

## Information about Libraries
## NeatText: Get the detail information : https://www.analyticsvidhya.com/blog/2021/10/cleaning-and-pre-processing-textual-data-with-neattext-library


A Python library for cleaning and preprocessing text data. It provides functions for removing unwanted characters, handling emojis, and extracting information from text.

## CountVectorizer:

A text preprocessing technique that converts text documents into numerical feature vectors. It creates a vocabulary of words and counts their occurrences in each document.
