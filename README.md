# sms-spam-detection
**end-to-end sms-spam-dectection project
**
**SMS Spam Classifier
**
This repository contains a project aimed at building a machine learning model to classify SMS messages as spam or ham (non-spam). The project involves data preprocessing, exploratory data analysis (EDA), text vectorization, and model building using various machine learning algorithms.

**Table of Contents
**
Dataset
Data Cleaning
Exploratory Data Analysis (EDA)
Data Preprocessing
Model Building
Performance Evaluation
How to Use
Dataset
The dataset used in this project is sourced from UCI Machine Learning Repository. It consists of 5572 SMS messages labeled as spam or ham. The dataset is loaded directly from a CSV file.

Data Cleaning
The initial dataset contained unnecessary columns and duplicate entries. The following steps were performed for cleaning the data:

Dropped columns 'Unnamed: 2', 'Unnamed: 3', 'Unnamed: 4'.
Renamed columns 'v1' to 'target' and 'v2' to 'text'.
Removed duplicate messages.
Exploratory Data Analysis (EDA)
Various statistical analyses were conducted to understand the dataset better:

Distribution of messages between spam and ham.
Analysis of message length, number of words, and number of sentences in spam vs. ham messages.
Visualization of the most common words in spam and ham messages using word clouds and bar plots.
Data Preprocessing
Text data was preprocessed through the following steps:

Lowercasing the text.
Tokenization: Splitting the text into words.
Removing special characters, stop words, and punctuation.
Stemming: Reducing words to their root form.
Model Building
Several machine learning models were built and evaluated for performance:

Naive Bayes (MultinomialNB): Known for its effectiveness in text classification tasks.
Support Vector Classifier (SVC): With sigmoid kernel.
Logistic Regression (LR)
Decision Tree Classifier (DT)
Random Forest Classifier (RF)
K-Nearest Neighbors (KNN)
The text data was vectorized using TF-IDF vectorizer with a maximum of 3000 features to convert text into numerical form suitable for model training.

Performance Evaluation
The models were evaluated based on accuracy and precision. The best-performing models were:

Multinomial Naive Bayes (MNB)
Support Vector Classifier (SVC)
Random Forest Classifier (RF)
These models were chosen based on their high precision and accuracy scores.
