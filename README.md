# Project Name
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
<ul>
<li><b>The variables significant in predicting the price of a house are: -</b></li>
GrLivArea, OverallQual_9, OverallCond_9, OverallQual_8, Neighborhood_Crawfor, Functional_Typ, Exterior1st_BrkFace, SaleCondition_Alloca, CentralAir_Y, TotalBsmtSF, Neighborhood_Somerst, TotalBsmtSF and Condition1_Norm

<li><b>How well those variables describe the price of a house?</b></li>
Here will see only top few variables

GrLivArea:an increase of 1 square foot of house area above ground, the price will increase by 1.09 to 1.11 times
OverallQual_9 & OverallQual_8: if the overall material and finish of the house is Very Good or Excellent, the price of house will increase by 1.08 to 1.13 times
Neighborhood_Crawfor: if Crawford is a nearby location, then the price of house will increase by 1.07 to 1.09 times
Functional_Typ: if the home functionality is typical, then the price of house will increase by 1.07 to 1.08 times
Exterior1st_BrkFace: if the exterior covering on the house is Brick Face, the price of house will increase by 1.07 to 1.08 times.
In a similar manner, we can deduct how well each variable describes the price of a house.

<li><b>Optimal value of lambda for Ridge Regression = 10</b></li>
<li><b>Optimal value of lambda for Lasso = 0.001</b></li>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- jupyter notebook
- librarys used are:
- numpy
- panda
- matplotlib
- seaborn
- feature_selection
- linear_model
- variance_inflation_factor
- statsmodels
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@IshrathFathima] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
