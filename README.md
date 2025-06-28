# Amazon-Customer-Reviews-Sentiment-Analysis
## Objective
- The aim of the project is to classify the seniment of amazon customer reviews. i.e. positive, neutral, negative using the VADER(Valence Aware Dictionary for sEntiment Reasoning) Model and Huggingface RoBERTa Transformers, look at the difference between model outputs from the two packages and compare the results.
## Steps followed:
- Step 1: VADER Sentiment Scoring. I used NLTK's (Natural Language Toolkit) SentimentIntensityAnalyzer to get negative, neutral, positive scores of the text.
- Setp 2: RoBERTa Pretrained Model -a transformers model pretrained on a large corpus of English data in a self-supervised fashion.
- The model not only accounts for the words but also the context related to other words.
## Results comparison and Conclusion
- RoBERTa provided more accurate results because it captured complex sentiment and contextual nuances. It's more effective at understanding context and relationships between words especilly in a scenario like this of product review. However, it's computationally more expensive and slower than VADER.
- VADER on the other hand is faster and easier to implement. However it struggled with long reviews and couldn't capture subtle nuances as effectively as RoBERTa. It's better suited for rapid sentiment analysis of social media posts, especially when speed is a priority and the text is relatively simple

## Dataset Link
[](https://www.kaggle.com/datasets/rachelkiarie/sentiment-analysisds)
