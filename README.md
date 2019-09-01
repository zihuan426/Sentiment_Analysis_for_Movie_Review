# Sentiment_Analysis_for_Movie_Review

### Introduction 
This is a sentiment analysis project I did at Data Application Lab, which is used to classify positive and negative movie reviews. After trying different machine learning model, I chose the one that have the best performance to build a web application, which can not only classify the sentiment but also visualize the important words that make significant contributions to the sentiment.

### Workflow
- Processed the raw Amazon review dataset with tokenization, normalization, tf-idf vectorization  
- Built Logistic Regression, Naïve Bayes, SVM classifiers to classify the sentiment and figured out the best model to be used in web application
- Designed embedding layer and LSTM layer via Keras with dropout technique to avoid model overfitting, and performed cross-validation on dataset and trained the best model with an accuracy of 86%
- Developed a web application via Flask

### Installation
To replicate the findings and execute the code in this repository you will need basically the following Python packages:

- Numpy
- pandas
- scikit-learn
- NLTK
- Keras

### Resource
Data Application Lab All rights reserved.
