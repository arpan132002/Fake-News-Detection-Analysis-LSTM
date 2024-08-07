# Fake-News-Detection-LSTM-Classification

## Overview
The **Fake-News-Detection-LSTM** project aims to build a robust machine learning model to detect fake news articles using Long Short-Term Memory (LSTM) networks. This project leverages natural language processing (NLP) techniques to classify news articles as real or fake based on their content.

### Attributes
- id: unique id for a news article
- title: the title of a news article
- author: author of the news article
- text: the text of the article; could be incomplete
- label: a label that marks the article as potentially unreliable
    - 1: unreliable
    - 0: reliable

**Download link:** https://www.kaggle.com/c/fake-news/data

**Glove Embedding link:** https://www.kaggle.com/anindya2906/glove6b?select=glove.6B.100d.txt

## Features
- **Data Preprocessing**: Includes text cleaning, tokenization, and word embedding using Word2Vec or GloVe.
- **LSTM Model**: Utilizes an LSTM network to capture long-term dependencies in the text data.
- **Model Training and Evaluation**: Trains the LSTM model on a labeled dataset and evaluates its performance using accuracy, precision, recall, and F1-score.
- **Visualization**: Provides visualization of model performance metrics and loss curves.
