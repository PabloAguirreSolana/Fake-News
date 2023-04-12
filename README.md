# Fake-News
The objective of this notebook is to run an LSTM model to detect Fake News on a Kaggle data set


## Context
Fake news can have severe consequences for businesses, governments, and society as a whole. By detecting fake news, businesses can avoid making decisions based on false information and prevent potential damage to their reputation.
The primary objective is to use LSTM to detect fake news effectively. 

## Dataset Details
WELFake is a dataset of 72,134 news articles with 35,028 real and 37,106 fake news. For this, authors merged four popular news datasets (i.e. Kaggle, McIntire, Reuters, BuzzFeed Political) to prevent over-fitting of classifiers and to provide more text data for better ML training.
The dataset contains four columns: Serial number (starting from 0); Title (about the text news heading); Text (about the news content); and Label (0 = fake and 1 = real).


## Model Used 
Long Short-Term Memory (LSTM) networks, a variation on RNNs, took Sequential Deep Learning to the next level by introducing a gated mechanism to handle long-term dependencies in data in a better manner and mitigate the Vanishing Gradient problem that RNNs are prone to. LSTMs were able to significantly improve the contextual memory and prediction quality of RNNs, and were widely adopted as the NLP architecture of choice in wide-ranging business applications before the advent of Transformer models.
