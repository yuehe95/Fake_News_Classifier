# Fake News Classifier

### Dataset used
Dataset can be found on Kaggle https://www.kaggle.com/c/fake-news/data

train.csv: A full training dataset with the following attributes:
- id: unique id for a news article
- title: the title of a news article
- author: author of the news article
- text: the text of the article; could be incomplete
- label: a label that marks the article as potentially unreliable (1: unreliable, 0: reliable)

test.csv: A testing training dataset with all the same attributes at train.csv without the label.

### Techniques used
Text preprocessing: Tokenization, Stemming, remove stop words, BOW / (TF-IDF)

Classifier: MultinomialNB Algorithm, Passive Aggressive Classifier, LSTM
