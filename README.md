# NLP_disaster_tweets
The following repository contains a python notebook which predicts wether a tweet is describing a natural disaster or not. It is a NLP and feature engineering project

In the project, the text of each tweet has been analyzed and some features related to each tweet have been created. For instance, the sentiment, formality or toxicity of the tweet might be relevant for the prediction. Moreover, a word embedding which transforms a text into a vector has been computed.

There are several saved datasets containing tweets information created for the simple purpose of accelerating the execution of the code. The notebook of the project is "NLP_project_notebook".
This project has used GloVe (Global Vectors for Word Representation); Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014, https://nlp.stanford.edu/projects/glove/ . Pre-trained word vectors are too large to include them in the repository, so there are several versions in https://github.com/stanfordnlp/GloVe which can be downloaded. Any version can be used in the notebook, there are only few naming changes to be made in the word2vec (word to vector) transformation section.

There is a competition in Kaggle which counts the F1-Score of this project's predictions. Link: https://www.kaggle.com/competitions/nlp-getting-started/data


