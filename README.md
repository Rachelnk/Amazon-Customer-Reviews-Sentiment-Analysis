# Amazon-Customer-Reviews-Sentiment-Analysis
## Objective
- The aim of the project is to classify the seniment of amazon customer reviews. i.e. positive, neutral, negative using the VADER(Valence Aware Dictionary for sEntiment Reasoning) Model and Huggingface RoBERTa Transformers.
- I looked at the difference between model outputs from the two packages and compare the results.
## Steps followed:
- Step 1: VADER Sentiment Scoring. I used NLTK's (Natural Language Toolkit) SentimentIntensityAnalyzer to get negative, neutral, positive scores of the text.
- Setp 2: RoBERTa Pretrained Model -a transformers model pretrained on a large corpus of English data in a self-supervised fashion.
- The model not only accounts for the words but also the context related to other words.

