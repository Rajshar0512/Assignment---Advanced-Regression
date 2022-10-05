# Project Name
> House price prediction problem


## Table of Contents
* [General Info](Contains the python code used to solve the above business problem and a PDF file conatining the asnwers to the subjective questions)
* [Technologies Used](#Pyhton- Jupyter)
* [Conclusions](#As per Ridge and Lasso Regression, we have generated the most significant variables predicting the house sales)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house. 

Also, determine the optimal value of lambda for ridge and lasso regression.

 Business Goal: 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market

Dataset used: https://ml-course3-upgrad.s3.amazonaws.com/Assignment_+Advanced+Regression/train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The optimum alpha value for Ridge is 7 and for Lasso is 0.0001
- The model performance by Ridge Regression was better than Lasso in terms of R2 values of Train and Test
- appropriate choice of alpha value of Ridge and Lasso is important as it may mask the top predictors


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy, Pandas, sklearn, seaborn


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@Rajshar0512] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->