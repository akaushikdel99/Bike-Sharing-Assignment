# Bike Sharing Assignment
> This assignment involves creating a multiple linear regression model to predict shared bike demand for BoomBikes, a US bike-sharing provider. The company has experienced revenue dips due to the Corona pandemic and aims to understand bike demand post-quarantine to plan their business strategy. The goal is to identify significant variables predicting bike demand and understand how they affect demand based on a large dataset of daily bike demands in the American market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#Contact)

## General Information
boomBikes, a US bike-sharing provider, has seen a decrease in revenues due to the Corona pandemic. They want to model the demand for shared bikes with the available parameters. This information will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. The model will be a good way for management to understand the demand dynamics of a new market. 

The objectives of this assignment are:

1. **Data Preparation**: Prepare the collected data for analysis.
2. **Model Building**: Build a model that can predict the demand for shared bikes based on various factors.
3. **Model Evaluation**: Evaluate the model's performance and its ability to predict bike demand.

## Conclusions
 - yr,holiday,temp,hum,windspeed,winter,Mist_Few_clouds,Light_Snow_Rain_Thunderstorm influences the rental of bike
 - Equation of the demand prediction is given by
    ypred= 0.2177 + yr * 0.2287 - holiday * 0.0973 + temp * 0.6058 - hum * 0.1419 - windspeed * 0.1724 + winter * 0.1125 -Mist_Few_clouds * 0.0485 - Light_Snow_Rain_Thunderstorm * 0.2382
 - We can see that holidays and unfavourable weather has detremental imact on demand
 - We can also say that temprature has a sginificant influence on bikes being rented


## Technologies Used
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodel


## Contact
Created by [@akaushikdel99] - feel free to contact me!
