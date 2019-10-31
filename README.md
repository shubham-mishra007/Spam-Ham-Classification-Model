# Spam-Ham-Classification-Model
Problem Statement: Using the Natural Language Processing Techniques, Predict for the test data whether the emails will be predicted as Spam or Ham.
------------------------------------------------------------------------------------------------------------------------------------------
Also, Solve the hurdles given in the problem statement below using modular programming:
1) Calculate the percentage of text in data shared which are spam?
2) Using count Vectorizer, fit the train data(70(ratio)).In the vocabulary got,find the longest token present.
3) Transform the train data ,fitted with count vectorizer. Using multinomial Naive Bayes classifier fit the model taking smoothing alpha value appropriately. Using the test data,find the area under the curve (AUC) score.
4) Calculate the average length of documents for spam documents? 
5) Calculate the average length of documents for not spam documents? 
6) Find the average number of digits per document for not spam documents?
7) Find the average number of digits per document for spam documents? 
8) Find the average number of non-word characters per document for spam documents? 
9) Find the average number of non-word characters per document for not spam documents?
10) Fit and transform the train data using Tfidf Vectorizer. Find 10 features each for the smallest and the largest tf-idf? Create 2 different series for these features,where each is sorted by tf-idf value and feature name(alphabetically).
11) Fit and transform train data using Tfidf Vectorizer and ignore terms with document frequency lower than 3. Using multinomial Naive Bayes classifier fit the model taking smoothing alpha value appropriately. Using the transformed test data,find the area under the curve (AUC) score.
12) Fit and transform train data using Tfidf Vectorizer and ignore terms with document frequency lower than 5. With the document-term matrix achieved and an additional feature, the length of document (number of characters), fit a Support Vector Classification model with appropriately taken regularization value. Using the transformed test data,find the area under the curve (AUC) score.
13) Fit and transform train data using Count Vectorizer and ignore terms with document frequency lower than 5 and use word n-grams from n=2 to n=5. With the document-term matrix achieved and an additional feature, the length of document (number of characters), fit a Logistic Regression model with appropriately taken regularization value. Using the transformed test data,find the area under the curve (AUC) score. ** Use character n-grams pass the parameter in analyzer='char_wb' which creates character n-grams only from text inside word boundaries. It makes the model more robust to spelling mistakes. Also, find 10 smallest and largest coefficients from the model along with the AUC score.

Also, Suggest a few Observations from the Above Analysis which could conclude to relevant results.
------------------------------------------------------------------------------------------------------------------------------------------
