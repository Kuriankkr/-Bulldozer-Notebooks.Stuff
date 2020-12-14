# Overview
This project is an outcome of the [fastai](https://www.fast.ai/) course that I had undergone. The course was spread over 9 lectures in which I was explained the working behind the working of **RandomForest Regressors** and how it could be applied to a real world dataset(discussed below). 

The jupyter notebook contrains an intial **Exploratory Data Analysis (EDA)** of the data, followed by **building the first model**, and then understanding the results, **fine tuning the hyperparameters**.The approaches taken, the insights obtained and the possible mistakes that could happen are discussed in detail in my notebook.

# Dataset
The link for the data is given [here](https://www.kaggle.com/c/bluebook-for-bulldozers/data). The data is sourced from Kaggle and it was part of a competition that was hosted by Kaggle.The dataset has 54 features of bulldozers including the sale price of bulldozers and the predictor variable. The goal behind the project is to build a model that would help predict the sales price of Bulldozers that range from the 1960's - 2011. The testing would be done on dataset from 2012.

There are 3 main datasets:
- **Train.csv** is the training set, which contains data through the end of 2011.
- **Valid.csv** is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
- **Test.csv** is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

# Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

# Features
Kaggle provides a data dictionary detailing all of the features of the dataset. This data dictionary can be viewed on Google sheets here (https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit#gid=1021421956)
