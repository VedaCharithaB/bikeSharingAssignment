# Bike Share case study
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Multiple linear regression is performed on the dataset.
- We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc. 
- The Boombikes bike rental dataset is being used.
- Company aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.


## Conclusions
- The R-squared value of the train set is 83.29% whereas the test set has a value of 80.7% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

- Developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set.
- The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

- The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set. 

- Concepts such as EDA, p-value, VIF, RFE were used and model building was done using statsmodels library

## Technologies Used
- numpy
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn


## Acknowledgements
- [References](https://github.com/ContentUpgrad/Linear-Regression)


## Contact
Created by [@vedacharitha] 
