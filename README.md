# SentimentAnalysis_Indonesian-Food
 Repo For Sentiment Analysis Project on Indonesian Food

This is a college project for Big Data Technology.
The goal of this project is to do a Sentiment Analysis for a certain topic.
Me and my team is trying to do a Sentiment Analysis on Indonesian Food based on Indonesians Twitter Tweets.

This project is made with Python Language using Google Colab.
The Libraries used are :
- Pandas (For opening the dataset and turning them into DataFrame)
- re (For Text Cleaning)
- Textblob (For counting the polarity of text)
- Deep_translator (For translating the text into English)

The Dataset is Indonesians Twitter Tweets around Indonesian Food.
We're using textblob library to count the polarity, but because textblob process
text in English, we have to translate the Indonesian-language text to English using textblob as well.
