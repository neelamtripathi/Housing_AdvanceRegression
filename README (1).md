# Project Name
> Housing_AdvanceRegression


Introduction:

A house is usually the single largest purchase an individual will make in their lifetime. Such significant purchase warrants being well-informed about what a house’s selling price should be; for the buyer, as well as the seller or real estate broker involved. The power of machine learning provides us with the tools we need to look at a large data set and spit out a predicted value, which was our main goal in this project. Using a dataset containing information on houses in Ames, Iowa, our team leveraged different machine learning techniques to predict sale prices based on both practical intuition and those observed through our exploratory data analysis and model fitting processes.

The general outline of the process was:

Imputing Missing Values
Exploratory Data Analysis
Feature Engineering/Dimension Reduction
Fixing Skewness and Outliers
Modeling
The Data Set:

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.

Observation

The above plot defines the way to decide the optimum value of alpha.
The point in which train and test score has less gap between them is the value which we take as an optimum value of alpha
Changes in Ridge Regression metrics:
Change Ridge Alpha 10 to 20
R2 score of train set decreased from 0.95 to 0.93
R2 score of test set increased from 0.88 to 0.90
R2score on training data has decreased but it has increased on testing data
Changes in Lasso metrics:
Change Ridge Alpha 0.001 to 0.002
R2 score of train set decreased from 0.89 to 0.87
R2 score of test set decreased from 0.86 to 0.84
R2score on training data and testing data decreased

Conclusion
From the above two techniques of Lasso and Ridge Regression, we can say that both almost having the same r2 value.
When comparing the complexity, it is better to use Lasso because as we have 221 variables, Lasso will make the feature selection among the present variables, but Ridge will not reduce columns, it will keep all 221 variables with the reducing the coefficient of variables.

## Technologies Used
- Python notebook

Libraries :
numpy, pandas, seaborn, matplotlib.pyplot, sklearn.linear_model, sklearn.model_selection,etc



## Acknowledgements
Neelam Tripathi
neelampython@gmail.com


## Contact
Created by [neelamtripathi] - feel free to contact me!

