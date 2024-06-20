# Stock-Sentiment-Analysis-Using-Machine-Learning-Techniques
## Project Overview
This project aims to perform sentiment analysis on financial news headlines related to stocks, utilizing natural language processing (NLP) techniques and machine learning models. It also includes a simulated portfolio management component based on sentiment predictions.
## Purpose:
This function fetches headlines related to stock news from Finviz, a financial news website.
## Implementation:
It uses requests and BeautifulSoup libraries to scrape HTML content and extract headline text.

headlines is a list containing fetched headlines.

Uses nltk for tokenization, stopwords removal, stemming, and lemmatization.

sklearn pipeline for seamless integration of text processing and classification stages.

Utilizes sklearn.metrics functions to calculate metrics based on predicted and actual labels (y_test and y_pred).
