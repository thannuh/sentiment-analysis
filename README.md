# sentiment-analysis
## Survey on Machine Learning Algorithms for IMDB review Sentiment Classification
### Workflow
#### Source Data Access
- Acquiring IMDB movie reviews with sentiment polarity labels dataset from Kaggle in csv format
#### Data Preprocessing
- Remove HTML Tags using HTML parser
- Remove contents inside square brackets using regex
- Remove special characters using regex
- Remove stopwords using nltk
- Stemming of words using nltk
#### Sampling of dataset
- 5k positive reviews and 5k negative reviews (total 10k reviews) for training. Remaining 40k reviews for testing.
- 10k positive reviews and 10k negative reviews (total 20k reviews) for training. Remaining 30k reviews for testing.
- 15k positive reviews and 15k negative reviews (total 30k reviews) for training. Remaining 20k reviews for testing.
#### Word Vectorisation
- Count vectoriser - Bag of Words model
- Tfidf Vectoriser - Term Frequency - Inverse Document Frequency model
#### Label Binarizer
- Converting the sentiment labels to 1s and 0s (Positive and Negative)
#### Modelling and testing
- Logistic Regression
- Multinomial Naives Bayes
- Support Vector Machines (poly)
- Support Vector Machines (linear)
- Support Vector Machines (rbf)
#### Final Report
- Accuracy Table
- Classification report using sklearn.metrics
#### Inference
- Algorithms with maximum accuracy
- Precision score for those algorithms
- A word on runtime and cost,time effective algorithm
