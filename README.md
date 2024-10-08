# Bike Share case study
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
A US bike-sharing provider has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, company aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

#### Business Goal:
To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

- Multiple linear regression is performed on the dataset.
- We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc. 
- The Boombikes bike rental dataset is being used.
- Company aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.


## Technologies Used
- numpy
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn


## Conclusions
- The R-squared value of the train set is 83.29% whereas the test set has a value of 80.7% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

- Developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set.
- The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.
- The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set. 

- Concepts such as EDA, p-value, VIF, RFE were used and model building was done using statsmodels library
- **Analysis from the built Model:**
    - When the Demand is High:
        - Seasonal Peaks: Bike rentals increase year over year, with the highest demand occurring between May and October, driven by favorable weather and increased outdoor activities.
        - Fall Season: Bike demand reaches its peak in the fall season, likely due to milder temperatures and more consistent weather.
        - Weather Conditions: Rentals are significantly higher on clear or partly cloudy days, where people are more inclined to rent bikes in pleasant weather.
        - Weekends and Holidays: Bike rentals experience a slight uptick on weekends and holidays, as people take advantage of their leisure time for recreational activities.
        - Ideal Temperature: Moderate temperatures drive the highest demand, as extreme weather conditions (too hot or too cold) negatively impact rental rates.
    - When the Demand is Low:
        - Spring Season Decline: Bike demand decreases during the spring season, potentially due to less predictable or inconsistent weather conditions.
        - Severe Weather Conditions: No bikes are rented during heavy rain, thunderstorms, or snow, as these conditions pose safety risks and deter users.
        - Light Rain and Snow: Even light rain or snow leads to a reduction in bike demand, though the drop isn't as sharp as during severe weather.
        - High Winds: High wind speeds negatively impact bike rentals, making it more difficult and less enjoyable to ride.
        - Extreme Temperatures: Both extreme heat and cold lead to a decline in rentals, as harsh weather conditions reduce outdoor activity.


## Acknowledgements
- [References](https://github.com/ContentUpgrad/Linear-Regression)


## Contact
Created by [@VedaCharithaB]  - feel free to contact me!
