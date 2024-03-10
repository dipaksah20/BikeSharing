# Bike Sharing Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Libraries Used](#libraries-used)
* [Conclusions](#conclusions)


## General Information

### Problem Statement 
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

### Business Goal 
It is required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

### Dataset used
- day.csv provided by Upgrad is used.

### Approach used
- Reading & Understanding data by EDA
- Prepare the train & test data for modelling 
- Training the model & Optimize the model
- Perform Residual Analysis 
- Predictions and evaluation on the test set 

## Technologies Used

- Python - version 3.11.5

## Libraries Used

- pandas
- numpy
- seaborn
- matplotlib
- sklearn
- statsmodels

## Conclusions
- R2 for Linear Regression Model 6 is 0.836 ie 83.6%
- Adjusted R2 for Linear Regression Model 6 is  0.832 ie 83.2% 
- The equation for the best fit line will be :                                                                                                                     
     **cnt = 0.2034 + ( 0.2339 * yr ) + ( 0.4917 * temp ) - ( 0.1497 * windspeed ) - ( 0.0682 * Season_Name_spring ) + ( 0.0479 * Season_Name_summer ) + ( 0.0818 * Season_Name_winter ) - ( 0.0483 * Month_Name_Jul ) + ( 0.0723 * Month_Name_Sept ) - ( 0.0450 * Weekday_Name_Sun ) - ( 0.2847 * Weather_Type_Light Snow & Rain ) - ( 0.0802 * Weather_Type_Mist )**

- Demand of bike sharing users depends positively on 
  - year 
  - temperature 
  - Summer season 
  - Winter season
  - September Month 
  

- Demand of bike sharing users depends negatively on 
  - Wind speed 
  - Spring Season
  - July Month
  - Sunday
  - Weather with Light Snow & Rain  
  - Weather with Mist                       
   

## Contact
Created by [@dipaksah20] - feel free to contact me!

