# Capstone-Project
Natural Language Processing: Text and Sentiment classification

This project aims to analyze the application of LSTM and Bi-LSTM on a small dataset financial of news articles.

The dataset, available on https://data.world/crowdflower/economic-news-article-tone, was initially published by CrowFlower on Dec 2015. This dataset includes 8000 news articles. Each article was judged on it relevance to US economy, if relevant, the positivity of its tone was evaluated using a 9-point scale.

We performed text classification on the relevance to US economy and sentiment analysis on the psoitivity of news that relevant to US economy. Support Vector Machine, XGBoost and Logistic Regression are employed as baseline models. This project introduced a structure that concatenates convolutional LSTM/BILSTM with TF-IDF vectors. The proposed model outperformed standardized LSTM/BiLSTM and baseline models including Support Vector Machine, XGBoost and Logistic Regression in both text classification and sentiment analysis.
