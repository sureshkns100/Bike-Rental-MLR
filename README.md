# Bike Rental Multiple Linear Regression
> Outline a brief description of your project.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project is an Assignment to create a Multiple Linear Regression model using the BoomBikes dataset to predict the demand for shared bikes.

- What is the background of your project?
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. Company want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
a. Which variables are significant in predicting the demand for shared bikes.
b. How well those variables describe the bike demands

- What is the business probem that your project is trying to solve?
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management 
to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet
the demand levels and meet the customer's expectations.
Further, the model will be a good way for management to understand the demand dynamics of a new market.
Goal :- Company want to understand the factors affecting the demand for these shared bikes in the American market. 
The company wants to know: Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands

- What is the dataset that is being used?
Bike Sharing dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Significant variables list based on VIF:
1. temp
2. windspeed
3. yr
4. season_summer
5. weathersit_mist

Comparision between Training and Testing dataset:
Train dataset R^2: 0.8325
Test dataset R^2: 0.7917
Train dataset Adjusted R^2: 0.822
Test dataset Adjusted R^2: 0.7585

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
numpy - version 1.26.4
pandas - version 2.2.2
matplotlib - version 3.8.4
seaborn - version 0.13.2
statsmodels - version 0.14.2
sklearn - version 1.5.1.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubsureshkns100} - feel free to contact me!
https://github.com/sureshkns100/Bike-Rental-MLR


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
