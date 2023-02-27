# Neural_Network_Charity_Analysis

## Overview
This analysis was done for Alphabet Soup to predict the successfulness of applicants if they were to be funded. A binary classifier will be created using the given dataset containing more than 34,000 organizations that have been funded over the years. 

## Results

### Data Preprocessing
* Our target variable in this model is the IS_SUCCESSFUL column.
* The variables that are the features within this model are AFFILIATION, USE_CASE, INCOME_AMT, ORGANIZATION, APPLICATION_TYPE, CLASSIFICATION, STATUS, ASK_AMT, and SPECIAL_CONSIDERATIONS.
* The variables that should be removed from the input data are the Name and Identification Number (EIN) as they are neither targets nor features.

### Compiling, Training, and Evaluating the Model
* This model contained an input feature and 2 hidden layers with an activation function of "Relu" and "Sigmoid". The first layer had 80 nodes and the second layer had 30.

![plot](Resources/Deliverable1.png) 

* The ideal target model was not achieved. The goal was 75% or above and 72% was the closest performance reached.

### Optimization 1

![plot](Resources/Deliverable2.png)


### Optimization 2

![plot](Resources/Deliverable3.png)


* In an attempt to increase the model performance, I changed the number of Epoch, the activation type, increased the number of hidden layers, and changed the number of neurons.

## Summary
After conducting the analysis and not being able to obtain a 75% accuracy performance, my suggestion would be to include more data or to try another model such as RandomForrestClassifier.



