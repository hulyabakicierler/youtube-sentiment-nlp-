# youtube-sentiment-nlp-
YouTube video descriptions sentiment classification using RoBERTa
Project Summary

This is a beginner-level NLP project to perform sentiment analysis on YouTube video descriptions. The objective is to label each description as Positive, Negative, or Neutral using a pre-trained RoBERTa model from Hugging Face (cardiffnlp/twitter-roberta-base-sentiment).

 Objective

Apply Natural Language Processing to real-world unstructured text.

Extract sentiment labels for each YouTube description.

Visualize dominant words and their sentiment orientation.

Share results as a first NLP project.

 Dataset

YouTube video descriptions (cleaned)

CSV format

description and clean_description columns used

 Model Used

cardiffnlp/twitter-roberta-base-sentiment

HuggingFace Transformers Pipeline

🔍 Steps Implemented

Data Preprocessing

Checked for nulls

Cleaned text (punctuation, lowercasing, stopwords removal)

Sentiment Analysis

Used Hugging Face pipeline("sentiment-analysis")

Added sentiment labels (POSITIVE, NEGATIVE, NEUTRAL) to dataframe

Visualization

Created a Word Cloud based on frequent terms

Calculated positive and negative frequency per word

Assigned dominant sentiment to key words

Sample Output

Word

Positive Freq

Negative Freq

Dominant Sentiment

tech

1.12

0.15

Positive

gadgets

0.80

0.00

Positive

 Tools & Libraries

Python

pandas, numpy

matplotlib, seaborn

HuggingFace transformers

WordCloud

 Languages

Türkçe ve İngilizce açıklamalar mevcuttur.

 Future Work

Train a custom classifier (optional)

Add UI for live prediction

 Author

This is my first NLP project using Transformers. Feedback welcome!
