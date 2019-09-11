# FakeNewsProject
Build a machine learning classifier that classify news articles as real or fake.   
## Teammates:   
Anthony Chan, Steven Chou
## Overview
1. __Data Collection:__  
  Data is colleted and preprocessed on Kaggle   
  Collection: https://www.kaggle.com/anthonyc1/gathering-real-news-for-oct-dec-2016  
  Preprocessing: https://www.kaggle.com/anthonyc1/fake-news-classifier-final-project

2. __Preprocessing__  
More preprocessing using stopwords removal and lemitization techniques.

3. __Text to Feature__  
Convert text to feature using TF-IDF (we also tried Word2Vec for this step but TF-IDF yields better results).

4. __Model Selection__  
Buid classifier using various classification algorithms from Scikit-learn.

5. __Classification__
Our best model yield 86% accuracy

## Development Enviroment
This project is developed in Python3 using Jupyter Notebook, hence the extension .ipynb.  
Dependent libraries include Numpy, Pandas, Scikit-learn, Gensim, Spacy and Matplotlib

## Result 

![ROC Scores](https://github.com/weiggwp/FakeNewsProject/blob/master/results/roc.png)  
![Metrics Table](https://github.com/weiggwp/FakeNewsProject/blob/master/results/classifiers.png)
