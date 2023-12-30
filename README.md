# ML2 Regression Model Assignment - Surprise Housing
> We are tasked to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

- The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

- The company wants to know:
	- Which variables are significant in predicting the price of a house, and
	- How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The best model for our prediction is the Lasso regression model with alpha as 0.0001, even though all the metrics are in favor of the Ridge model.
- If we need a simpler model with lesser parameters to consider then we should go with Lasso as it tends to reduce the number of features by making their coefficient to zero. Which will avoid overfitting and error in unknown data sets

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - 1.3.5
- numpy - 1.21.6
- matplotlib - 3.1.1
- seaborn - 0.12.2
- statsmodels - 0.10.1
- sklearn - 0.21.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


