# Bike Sharing Assignment
> This assignment is a programming assignment wherein multiple linear regression model has to be built for the prediction of demand for shared bikes.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Goal](#business-goal)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Model Results](#model-results)
* [Conclusion](#conclusion)
<br />

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
US bike-sharing provider BoomBikes, a Mobility Services firm has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

Essentially the company wants :

* To understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19, by creating a linear model.<br />

* To identify the variables affecting their revenues i.e. Which variables are significant in predicting the demand for shared bikes.<br />

* To know the accuracy of the model, i.e. How well those variables describe the bike demands

They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

<br />

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Business Goal
Need to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

The company wants to know which variables are significant in predicting the demand for shared bikes and how well those variables describe the bike demands
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Approach:
- Reading and Understanding the Data
- Visualising the Data
- Exploratory Data Analysis
- Data Preparation for Modelling
- Splitting the Data into Training and Testing Sets
- Rescaling the Features
- Building a Multiple Linear regression model
- Residual Analysis of the train data
- Making Predictions Using the Final Model
- Model Evaluation


## Technologies Used
- numpy - version 1.24.3
- pandas - version 2.0.3
- matplotlib - version 3.7.2
- seaborn - version 0.12.2
- statsmodels - version 0.14.0
- sklearn - version 1.3.0
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Model Results
* R-squared 		 - Training Set: 0.824, Test Set: 0.812
* Adjusted R-squared - Training Set: 0.816, Test Set: 0.803
* RMSE				 - Training Set: 0.094, Test Set: 0.095

## Conclusion
Significant variables to predict the demand for shared bikes:
</br>
* temp
* yr
* season (winter, spring)
* windspeed
* weatersit (Light Snow, Mist)
* mnth (Nov, Dec, Jan)


## Contact
Created by [@rajani2024] - feel free to contact me!
