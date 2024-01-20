# GlowByte_hackaton

## Objective

Develop a reliable and accurate model for forecasting the next day's hourly energy consumption for Kaliningrad region using available historical data and relevant variables.

## Data Description

*date* - date

*time* - time, time is represented in the range 0 - 23, which means 24
hours in a day

*target* - actual consumption on the specified date 

*temp* - actual temperature on the specified date 

*temp_pred* - temperature forecast for the specified date 

*weather_fact* - actual weather on the specified date 

*weather_pred* - weather forecast for the specified date

## Results

A detailed preprocessing of the data and the creation of a large number of additional features from the information already available were performed. Predictions for the coming day were also used as features. 
LGBM was chosen as the model. MAE : 5.91.
