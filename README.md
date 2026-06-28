# PROJECT---Sentiment-Analysis-Data-Science-
Amazon Reviews Sentiment Analysis using VADER and ROBERTA
This project focuses on performing Sentiment Analysis on the Amazon Fine Food Reviews dataset using two different Natural Language Processing (NLP) techniques: VADER (Valence Aware Dictionary and sEntiment Reasoner) and RoBERTa, a transformer-based pretrained model from Hugging Face. The primary objective of this project is to classify customer reviews into positive, neutral, and negative sentiments and compare the effectiveness of a rule-based approach with a deep learning model.

The project starts with loading and exploring the dataset using Pandas. Basic Exploratory Data Analysis (EDA) is performed to understand the distribution of review ratings, identify important features, and visualize customer feedback patterns. The review text is then preprocessed using the NLTK library, where tokenization, part-of-speech tagging, and named entity recognition are demonstrated before sentiment analysis.

In the first stage, the VADER Sentiment Analyzer calculates four sentiment scores for each review: positive, negative, neutral, and compound. These scores are merged with the original dataset and visualized using Matplotlib and Seaborn to observe how sentiment varies across different star ratings.
