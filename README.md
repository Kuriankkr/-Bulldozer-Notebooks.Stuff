# **Bluebook for Bulldozers**

# Overview
This project is an outcome of the [**fastai**](https://www.fast.ai/) course that I had virtually taken. The course was spread over 9 lectures in which I was taught how to leverage data and find insights from it.

The jupyter notebooks present in this repository has all the work I did as a part of the course. It contains an intial **Exploratory Data Analysis (EDA)** of the data, followed by **building the first model**, **understanding the results** and finally **fine tuning the hyperparameters**.The approaches taken, the insights obtained and the possible mistakes that could happen are discussed in detail in my notebook after each section.

# Dataset
The link for the data is given [here](https://www.kaggle.com/c/bluebook-for-bulldozers/data). The data is sourced from Kaggle and it was part of a competition that was hosted by Kaggle.

The dataset has 54 features of bulldozers including the sale price of bulldozers and the predictor variable. The goal behind the project is to build a model that would help predict the sales price of Bulldozers that range from the 1960's - 2011. The testing would be done on dataset from 2012.

There are 3 main datasets:
- **Train.csv** is the training set, which contains data through the end of 2011.
- **Valid.csv** is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
- **Test.csv** is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

# Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

# Features
Kaggle provides a data dictionary detailing all of the features of the dataset. This data dictionary can be viewed on Google sheets [here](https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit#gid=1021421956)

# Technology Used
<p>
  <img width="250" align='left' src="https://github.com/Kuriankkr/Bluebook-for-Bulldozers/blob/master/Images/1_cxfqR8NAj8HGal8CVOZ7hg.png">
</p>
<p>
  <img width="250" align='left' src="https://github.com/Kuriankkr/Bluebook-for-Bulldozers/blob/master/Images/87a50dce-a64d-4747-b152-30f2f13e80ef.png">
</p>
