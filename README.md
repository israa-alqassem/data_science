## Data Science
This repository contains various data science assignments and projects which I enjoyed solving/working on.
* In `./car_listings` there are a classification and regression problems
  * Predict product tier class (i.e., Basic, Premium, Plus) using Random Forest Classifier
  * Predict detail views using Gradient Boosting Regressor
* In `./lstm_seq2seq`, there is an example of a character-level recurrent sequence-to-sequence model for translating short English sentences to French, using TensorFlow v2.2.0 and Keras v2.3.0 and ran on a GPU machine, GeForce RTX 2080
* In `./restaurant_reviews`, I coded a simple solution for a simple sentiment analysis NLP classification task, the goal is to predict whether a customer's review is positive or negative, I use nltk for preprocessing the reviews, and my solution offers a bucket of different classifiers, e.g., GaussianNB, RandomForestClassifier, LogisticRegression
* In `./movie_recommendations` I use item based collaborative filtering technique to recommend movies to a user based on his/her favourite movie list. I got the data from <a target="_blank" href="https://grouplens.org/datasets/movielens/">MovieLens Latest Datasets</a>. This movie rating data was collected between 1996 and 2018 from 610 users, it contains 100836 ratings and 9742 movies.

 
 


### Issue viewing ipynb in github

Sometimes github fails to render the jupyter notebooks, .ipynb files.
If you encounter such an issue use nbviewer online to view the .ipynb file, you don't need to install anything.

* Open https://nbviewer.jupyter.org/
* Copy and paste the link to the notebook you want to view


This workaround solution was suggested in this <a target="_blank" href="https://github.com/iurisegtovich/PyTherm-applied-thermodynamics/issues/11">post</a>.<br/>
