# Disaster Tweets

Kaggle competition about Disaster Tweets.
https://www.kaggle.com/c/nlp-getting-started/data

## Data

Keywords don't always match.
Location seems not so useful, but we could see if some countries / areas that are more likely.

- Location is user defined
  URLs which could contain image, video, etc.
  Could be vulgar, offensive, profane.
  Language? Do they have multiple languages

## Approach

Preprocessing

- tokenise
- remove stop words
- POS tagging
- Lemmatisation

words with same meanings?

Words to numbers

- bag of words
- doc2vec

Models

- tree classifier
- logistic regression
- neural network
