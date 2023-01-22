# Project Name
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file provided.

 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information) :- Prediction is done by doing regularization using Lasso and Ridge regression
* [Technologies Used](#technologies-used) : - Model is evaluated by doing regularization using Lasso and Ridge regression
* [Conclusions](#conclusions) : - It is important to have good accuracy of model along with significant feature selection. In this house price prediction model, I would prefer to choose Lasso.
* [Acknowledgements](#acknowledgements)
Below are some of the features, which are having negative correlation with salesprice, i.e., decrease in their values can lead to increase in sales price:-
1. PropAge - Age of property
2. MSSubClass - Type of dwelling involved in the sale

While few below features are having positive correlation with salesprice, i.e., increase in their values can lead to increase in sales price:-
1. OverallQual - Rates the overall material and finish of the house
2. GrLivArea - Above grade (ground) living area square feet
3. GarageArea	 - Size of garage in square feet
4. OverallCond - Rates the overall condition of the house
<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project? - A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file provided.

- What is the business probem that your project is trying to solve? - The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. The company wants to know:
1.Which variables are significant in predicting the price of a house, and
2.How well those variables describe the price of a house.
- What is the dataset that is being used? - train.csv



## Conclusions
- Conclusion 1 from the analysis - Lasso regression method is more effective in this case
- Conclusion 2 from the analysis - Lasso did feature selection to 19 with alpha = 0.01
- Conclusion 3 from the analysis - Accurancy is almost same on train and test set in lasso. R2 is 0.852(train) and 0.855(test)
