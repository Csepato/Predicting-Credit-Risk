![LendingClub](images/Lending-club.png)

# Predicting Credit Risk

In this project, I will be building a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not. 

## Background

LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.

I will be using this data to create machine learning models to classify the risk level of given loans. Specifically, I will be comparing the Logistic Regression model and Random Forest Classifier.

## Converting categorical data to numeric
![convert categorical data](images/Convert-categorical-data.png)

## Fitting a LogisticRegression model
![train logistic regression model](images/logistic-regression.png)

## Fitting a RandomForestClassifier model
![train random forest model](images/random-forest.png)

## Results
When comparing the two models without any scaling, the random forest model performed better on the test data. The lack of scaling seem to have had an impact on the test data.

With scaling the logistic regression model performed better than random forest model with a 0.66 accurancy score.
The random forest model decreased in accuracy from 0.64 to 0.56 with scaled data.  
Random forest is a tree-based model and is not affected by feature scaling. 
The model does not rely on scaled data to make accurate predictions unlike the logistic regression model.

In conclusion, even though the model was able to produce a 0.66 accuracy this may not be sufficient for credit worthiness purposes. 
Money may be lost if loan decisions are solely based on this model.     
