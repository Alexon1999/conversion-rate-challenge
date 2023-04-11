# <p align="center">Conversion Rate Challenge</p>

<p align="center"> <img src="dsw_logo.png" width="250"> </p>

## Context 

[Data Science Weekly](www.datascienceweekly.org) is a newsletters created by independent data scientists. These data scientists would like to understand better the behaviour of the users visiting their website. To do so, they open-sourced a dataset containing some data about the traffic on their website and held a competition aiming at building a machine learning model that allows to predict the conversions (i.e. when a user will subscribe to the newsletter). They would like to analyze the parameters of the model to highlight features that are important to explain the behaviour of the users, and maybe discover a new lever for action to improve the newsletter's conversion rate. To assess the rankings of the different competing teams, the site ownerss decided to use the f1-score.

The datasets used for this project include:
- labelled dataset (conversion_data_train.csv) that was separated into train that is used to train a model and the test to test the model. After the performance of a given model had been evaluated, the train and test parts of this labelled dataset were joined together again and the whole dataset was used for training the model once more.
- After such training, the model was used to make predictions on the unlabelled dataset (conversion_data_test.csv). The predictions of the model were sent to Jedha instructors who compared the predictions with the true labels and communicated the resulting f1-score. 

## Goals of the project

 - Do exploratory data analysis of the dataset
 - Train a baseline model
 - Improve the f1-score by training other models or by other means (feature engineering/selection, grid search, regularization...)
 - Analyse the parameters of the best model and give recommendations to improve the newsletter's conversion rate.


## Project files

1. **data** folder all the datasets are stored
2. **models** folder is where all the models were persisted
3. **submissions** is where all the submissions.csv are stored
4. **automl.ipynb** is a notebook, i use to test the package **automl** to select best models that fit my data.
5. All other notebooks correspond to different models and technics i used to come with a state-of-the-art ML model.