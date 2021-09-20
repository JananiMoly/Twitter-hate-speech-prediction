While social media brings the world closer, sometimes it unfortunately becomes a misused tool to spread hatred and misinformation. Good news is that, we can tackle the downside to using social media by creating NLP and ML models that can detect hate speech and enable relevant stakeholders to take appropriate action on those accounts that instigated it. 
In my code, I am training a model on tweets dataset to predict and label hate speech. Since the exact input-output mapping to this dataset exist, using a supervised machine learning algorithm works!

I used various functions in the NLTK library to preprocess text corpus, tokenize them and convert the tokens to input vectors. The input vectors are then fit into a supervised classification machine learning algorithm - Logistic Regression. Logistic Regressor identifies and predicts hate speech and highlights it as 1. 

The model had an accuracy percentage of **95% on test dataset.** 

*Functions in NLTK library:* tokenize.TweetTokenize, nltk.stopwords, feature_extraction.text.TFIDF Vectorizer

*Functions in Sklearn library:* preprocessing.model_selection, metrics.accuracy_score, mertics.classification_report

*ML Algorithm:* linear_model.LogisticRegression
