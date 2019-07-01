# Project 2 - Ames Housing Data and Kaggle Challenge

Welcome to Patrick Wales-Dinan's Project 2 Kaggle Challenge readme

This lab was incredibly challenging. We had to extensively clean a date set that was missing a lot of values and had TONS of categorical data. Then we had to decide what features to use to model that data. After that we had to build and fit the models making decisions like whether to use polynomial features, dummy variables etc, log scaling features or log scaling the depended variable.

After that we had to re run our model over and over again, looking at the different values of $\beta$ and seeing if they were contributing to the predictive power of the model. We had to decide if we should throw those values out or if we should leave them. We also had to make judgement calls to see if our model appeared to be over fitting or suffering from bias. 

There are 2 notebooks associated with this:
1. Project_2_FINAL.ipynb
2. Project_2_Graphs & Relationships.ipynb

There contents are laid out below:

## Contents: Project 2 Final
- [Data Import](#Data-Import)
- [Feature Creation](#Feature-Creation)
- [Choosing the Features](#Feature-Choice)
- [Log Scaling](#Log-Scaling-Independent-Variables)
- [Cleaning the Data and Modifying the Data](#Cleaning-&-Creating-the-Data-Set)
- [Modeling the Data](#Modeling-the-Data)
- [Model Analysis](#Analyzing-the-model)

## Contents: Graphs and Relationships
- [Feature Creation](#Feature-Creation)
- [Looking at Correlations](#Correlation-Investigation)
- [Pairplots of numerical data](#Pairplots)
- [Examining the Neighborhood Variable](#Looking-Specific-Relationships-Relative-to-Neighborhood)
- [Looking at additional relationships](#Other-Relationships)
- [Taking a Deeper Look at Log Transformations](#Log-Transformations-Cont.)

When running the model I found the most success with few variables:

My top prediction has a MSE of 22776.11 on the private score which would have resulted in the top mark unfortunately that was not one of the models that I submitted. My eventual model ended up with a score of 28131.80 on the private leaderboard, good enough for 5th place.

I also encourage you to view my presentation on the data at Project_2_Presentation.pptx

Finally the predictions folder contains many but not all of my predictions for the model. 

the csv file labeled wd_prediction_1.csv contains the predictions that had the lowest MSE

Overall this project was a fantastic experience!