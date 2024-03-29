Ames Housing Data and Kaggle Challenge

Welcome to Patrick Wales-Dinan's Kaggle Challenge readme

I started by extensively cleaning a date set that was missing a lot of values and had TONS of categorical data. Then we had to decide what features to use to model that data. After that we had to build and fit the models making decisions like whether to use polynomial features, dummy variables etc, log scaling features or log scaling the depended variable.
This was quite enjoyable. I attempted to use data from the Ames  I began by extensively cleaning a data set that was missing a lot of values and had TONS of categorical data. The next step was to determine what features to try to use. After that we had to build and fit the models making decisions like whether to use polynomial features, dummy variables etc, log scaling features or log scaling the depended variable.

After that we had to re run our model over and over again, looking at the different values of $\beta$ and seeing if they were contributing to the predictive power of the model. We had to decide if we should throw those values out or if we should leave them. We also had to make judgement calls to see if our model appeared to be over fitting or suffering from bias. 

There are 2 notebooks associated with this:
+ [Final.ipynb](https://github.com/pwalesdi/Ames_Housing_Data/blob/master/FINAL.ipynb)
+ [Graphs_&_Relationships.ipynb](https://github.com/pwalesdi/Ames_Housing_Data/blob/master/Graphs_%26_Relationships.ipynb)

There contents are laid out below:

## Contents: Final
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

## Visual Examples
### Home Age vs. Price
![alt text](https://github.com/pwalesdi/Ames_Housing_Data/blob/master/assets/new_homes.png "Relationship between home age and prices")

### Quality rating of a home in Ames vs. Price (sorted by neighborhood)
![alt text](https://github.com/pwalesdi/Ames_Housing_Data/blob/master/assets/qual_neigh.png "Relationship between the quality rating of a home & price")

### Total above ground living area of a home in Ames vs. Price (sorted by neighborhood)
![alt text](https://github.com/pwalesdi/Ames_Housing_Data/blob/master/assets/gl_neigh.png "Relationship between the home size & price")

## Findings

When running the model I found the most success with few variables:

My top prediction has a MSE of 22776.11 on the private score which would have resulted in the top mark unfortunately that was not one of the models that I submitted. My eventual model ended up with a score of 28131.80 on the private leaderboard, good enough for 5th place.

I also encourage you to view my presentation on the data at Ames_housing_Presentation.pptx

Finally the predictions folder contains many but not all of my predictions for the model. 

the csv file labeled wd_prediction_1.csv contains the predictions that had the lowest MSE

Overall this project was a fantastic experience!
