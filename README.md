# ML-Regression_Time_Series

## Predicting the sale price of Bulldozers using Machine Learning
### 1. Problem Definition
> How well can the future sale price of a bulldozer, given its characteristics and previous examples be predicted?

### 2. Data
The data is downloaded from the Kaggle Bluebook for Bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data

The data for this competition is split into three parts:

**Train.csv** is the training set, which contains data through the end of 2011.
**Valid.csv** is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
**Test.csv** is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

### 3. Evaluation
The evaluation metric for this competition is the **RMSLE** (root mean squared log error) between the actual and predicted auction prices.

For more evaluation info: https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

Note: The goal for most regression evaluation metrics is to minimize the RMSLE.

### 4. Features
Kaggle provides a data dictionary detailing all of the features of the dataset. You can view the data dictionary at: https://www.kaggle.com/c/bluebook-for-bulldozers/data
