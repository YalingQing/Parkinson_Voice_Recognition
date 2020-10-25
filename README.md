# Parkinson_Voice_Recognition

## Environment 
conda 4.8.3

Python 3.7.4

sklearn 0.21.3

## Dataset 
UCI Parkinson voice recording database

http://archive.ics.uci.edu/ml/datasets/Parkinson+Dataset+with+replicated+acoustic+features+\

Dataset contains 46 attributes and 240 recordings from 80 participants. Each participant has 3 replicated recordings. 

## Description:
average dataset: dataset that averages 3 replicated recordings attribute value for each participant

record 1 dataset: dataset that takes the 1st recording attribute value for each participant

record 2 dataset: dataset that takes the 2nd recording attribute value for each participant

record 3 dataset: dataset that takes the 3rd recording attribute value for each participant

reduced  dataset: average dataset undergoes dimension reduction

Knn, decision tree, naive bayes, logistic regression, bagging random forest, bagging knn classifiers are used for each dataset classification task. 

** (diff) means classifier models are optimized independently on each dataset. 

** NO (diff) means using same classifier model with averaged dataset. 
