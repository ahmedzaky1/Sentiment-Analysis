## Introduction
Sentiment analysis, also known as opinion mining, is a crucial task in natural language processing (NLP) that involves the identification and classification of sentiments expressed in textual data. With the exponential growth of social media platforms, review websites, and online forums, there is an abundance of user-generated content that contains valuable insights into people's opinions, feelings, and attitudes towards various topics, products, or services.

The primary objective of sentiment analysis is to automatically determine the sentiment conveyed in a piece of text, which can be broadly categorized into positive, negative, or neutral. By leveraging machine learning algorithms and NLP techniques, sentiment analysis enables businesses and organizations to gain actionable insights from large volumes of textual data, such as customer feedback, product reviews, social media posts, and news articles.

## Import Libs
1. numpy
2. pandas
3. matplotlib
4. seaborn
5. nltk

## Pre-processing Data
Before performing sentiment analysis, it's essential to preprocess the text data to ensure optimal model performance and accuracy. 
This preprocessing step involves several key tasks, such as tokenization, removing stopwords, and stemming or lemmatization. 
We'll utilize the Natural Language Toolkit (NLTK), a popular Python library for NLP, to perform these preprocessing tasks.

1. Tokenization
Tokenization involves breaking down the text into individual words or tokens.
NLTK provides various tokenizers to accomplish this task, including word tokenization and sentence tokenization.

2. Removing Stopwords
Stopwords are common words that typically do not contribute much to the overall meaning of the text and can be removed to improve the efficiency of the analysis.

3. Stemming or Lemmatization
Stemming and lemmatization are techniques used to reduce words to their base or root forms. NLTK provides modules for both stemming and lemmatization.

## Training and Evaluation

1. Training the Model
 After preprocessing the text data and extracting relevant features, we proceed to train the sentiment analysis model using a supervised learning algorithm.
 In this notebook, we utilize the Multinomial Naive Bayes classifier from the scikit-learn library,which is well-suited for text classification tasks.

2. Evaluating the Model
Once the model is trained, we evaluate its performance on a separate test dataset to assess its ability to generalize to unseen data.

## Model Deployment
After training the sentiment analysis model, you may want to deploy it to make predictions on new data in real-world applications. 
