# Bike Sharing Assignment

The project is intended to deduce features affecting the demand for renting bikes and a good model to understand demand dynamics of new market as per 


## Table of Contents
* [Overview](#Overview)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#Contributors)

****

## Overview

Since we want multiple feature determining relationship with demand/ count, it would require to apply multiple linear regression model

1. Understand Data
2. Data Analysis - Univariate, Bivariate, Multivariate
3. Preprocessing data
    a. Handle missing values
    b. Dummy variable creation/ encode categorical variables
4. Split Data (train set, test set)
5. Scale numerical variables
6. Feature Selection (correlation matrix/ heatmap/ pairplot, RFE)
7. Modelling (Assess the model’s performance using metrics such as Mean Squared Error (MSE) and R-squared ( R^2 ))
8. Residual Analysis of the train data
9. Making Predictions
10. Model Evaluation


## Technologies Used
- Python - v3.11.5
- Python Libraries
  - pandas - v2.2.2
  - numpy - v1.26.4
  - plotly - v5.22.0
  - matplotlib - v3.9.0
  - seaborn - v0.13.2
  - statsmodels - v0.14.2
  - scikit-learn - v1.5.0
- Jupyter Notebook - v7.0.8

## Conclusions

Demand of bikes depend on following features:
year
temperature
windspeed
season__spring
weathersit__Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
weathersit__Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist

## How well those variables describe the bike demands:
Bike demand counts are lower in case of weather with Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mis
Bike demand counts are higher at higher temperature
Bike demand counts are lower in spring
Bike demand counts are lower in case of weather with Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds


## Recommendations
Cloudy, Misty, rainy kind of weathers since travelling by bikes can become a hastle for the customers so they can even allow overnight charges discount and call for help/ pick drop features
During higher temperatures operations should be ramped up to keep up with the demand
During lower or pleasant temperatures more marketing campaigns can be targetted to drive more customers to use bikes
Since spring is usually holiday season better sales model like rent a bike for city tour or tour to nearby holiday spots or overnight rentals can be promoted

---------------------------------------------------------------------------------------------------------
## Contributor
Sonal Jatav [@sonal-jatav]
