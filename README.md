## Project Title
# Sentiment Analysis on IMDB Reviews
## Goal
Part A: IMDb Movie Review Sentiment Analysis - To classify IMDb movie reviews as positive or negative using NLP preprocessing and machine learning models.
Part B: News Article Classification - To classify news articles into different categories based on their headline and short description.
## Insights 
Part A: IMDb Movie Reviews
Dataset was balanced (equal distribution of positive and negative reviews).
Text preprocessing steps included:
Removing HTML tags (using BeautifulSoup).
Tokenization, stopword removal, stemming/lemmatization.
Feature extraction with Bag of Words and TF-IDF.
Models tested:
Logistic Regression → Accuracy: 0.89
Linear SVM → Accuracy: 0.88
Insight: Logistic Regression performed slightly better, making it the best choice for sentiment classification in this case.

Part B: News Article Classification
Preprocessing included dropping irrelevant/missing-value columns like keywords, link, and combining headline + short description into a single feature.
Data showed mild class imbalance, but not severe enough to harm model performance.
Applied text preprocessing and feature engineering for classification.
Insight: Headline and short description together carried enough signal to classify articles into categories effectively.
