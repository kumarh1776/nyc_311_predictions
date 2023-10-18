# nyc_311_predictions
Using weather data to predict 311 calls in NYC

311 calls are non-emergency requests. Examples include noise complaints, parking issues, heat/hot water concerns. 

Given a history of calls from 2016-2018 and weather data from the same time period, I sought to predict the quantity & distribution of 311 requests in NYC over a seven-day period.

The main skills employed here are:

- Visualization --> time series & mapping charts are the biggest part of the EDA process for both the 311 data and the weather data.
- Feature Engineering --> built out predictive features using interaction variables of the weather and/or 311 data
- Random Forest Model --> used a random forest model with RFE improvements to select appropriate features to predict on
