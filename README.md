# Rental Price Regression Project
Canada Rent regression project based off 2024 data

Creators:
- Flora Wong
- Kun Bi
- Naudeen Stewart

## Introduction
  In this project we will examine the factors that influence the rental prices of units acroos Canada in 2024.
We will use the [dataset](canada_rent.csv) obtained from [rentfaster.ca](https://www.rentfaster.ca/?utm_source=OOH&utm_medium=sign&utm_campaign=ca).
The data will be statistically analysed and then fitted to different regression models in hopes of finding an accurate predictor of the rental prices.

## Project Contents
  We begin with exploring the dataset as whole and then deciding on the most influential factors that can be used for analysis per our capabilities.
The data is cleaned of missing values and unwanted columns. Data columns are also regrouped along with certain values in order to simplify the data according 
to our analysis goals and feature importance. An anaysis is performed to explore the relationship between the Targert variable "Price" and all other features.
Regression models are then fitted to the data and examined. The most accurate performing model is then chosen to make final predictions.

### Regression models used:
- LassoCV
- RidgeCV
- ElasticNetCV
