# Text-Mining-and-Sentiment-Analysis
# YouTube Comment Spam Detection and Sentiment Analysis Using Naive Bayes
This project when deployed can be used to enhance content moderation by classifying comments as spam or ham and analyzing their sentiment.

# What I Did

Preprocessed 1,956 YouTube comments with tokenization, stopword removal, and stemming.
Applied the Naive Bayes classifier for spam detection and VADER for sentiment analysis.
Addressed class imbalance using RandomOverSampler and evaluated model performance.

# Tools and Packages
Python (NLTK, Scikit-learn, Matplotlib, Seaborn).
Naive Bayes Classifier for spam detection.
VADER for sentiment scoring and WordCloud for visualizing keywords.

# Results 
Naive Bayes: 63% accuracy, with 79% precision and 62% recall.
Sentiment analysis revealed most comments were neutral to positive, with minimal negative spam.

This approach demonstrates the importance of combining spam detection with sentiment analysis to enhance user experience and platform integrity.
