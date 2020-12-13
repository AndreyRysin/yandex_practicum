# Description

The online store is launching a new service: now users able to edit and add the product descriptions on their own. It's necessary to develop a tool which will search for toxic comments and send them for moderation.

### Metrics

*F1* > 0,75.

# Essential

* deep learning (text processing)
* TF-IDF
* BERT

# Stack

* pandas
* numpy
* scikit-learn
* lightgbm
* catboost
* torch
* transformers
* nltk

# Pipeline

* TF-IDF: deleting stop-words, tokenization, lemmatization
* BERT: tokenization with transformers, forming embeddings
* feature engineering
* ML models building
* final report
* appendix with raw results
