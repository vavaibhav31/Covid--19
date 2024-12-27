# Covid-19
This is a repository for Regression Analysis over Covid-19
# Data
The dataset used in this is taken from other Github repo. The dataset contains a number of missing values which is being replaced by 'Unknown' as it was categorical value.
# Statistical Analysis
To move further, done some analysis which helps to know how columns signify with each other.This helps in verfying that 'Target' which I decided should be taken or not.
# Visualisation
Few of the graphs have been plotted which gives a basic overview.
# Implementing Model
A total of four different models has been used such as Linear Regression, Lasso, Ridge, RandomForestRegressor.
The best performing model comes out to be Linear Regression rather than RandomForestregressor as it was increasing Time Complexity and leading to increase in error.
# Analysis
At last Residual Analysis of the best performing model where the distribution of the plot indicates that model performs well over unseen data when compared to plot of train data. So,we can conclude that model is neither overfitting nor underfitting.
