# ENERGY-CONSUMPTION-FORECAST-ANALYSIS
# Predictive Analysis on Energy Consumption from the period of 2020–2021 using Microsoft Excel as part of my Data Science project at 10Alytics

# INTRODUCTION
Energy Consumption prediction is a crucial tool in managing and planning for future energy needs. It enables utilities, businesses, and governments to optimize their operations, reduce costs, and promote energy efficiency. With the help of machine learning algorithms and statistical models, accurate energy forecasting can be achieved, ensuring a reliable and sustainable energy supply for the future.

# TASK
My task was to analyze Energy Consumption data from 2020-2021 and predict future consumption using various forecasting techniques, such as the Naive Approach, Moving Average, Exponential Smoothing, Forecast sheet, and Simple Linear Regression. The aim was to determine the most effective approach for the organization. To evaluate the accuracy of the forecasts, three metric parameters were used: Mean Absolute Deviation (MAD) or Mean Absolute Error (MAE), Mean Squared Error (MSE), and Mean Absolute Percentage Error (MAPE).

# INSIGHTS
The blue line represents the actual sales while the orange line represents the forecast sales. 

Using the Naïve Approach:
MAD = 1,652.175
MSE = 3,644,347.838
MAPE = 17%
Accuracy = 83%
 
Using the Moving Average (3 Quarters):
MAD = 2,738
MSE = 9,955,926
MAPE = 29%
Accuracy = 71%

Using the Exponential Smoothing 
MAD = 1,926.60
MSE = 5,254,855.20 
MAPE = 20%
Accuracy = 80%

Using the Forecast Sheet:
MAD = 2,902
MSE = 11,468,510
MAPE = 35%
Accuracy = 65% 
 
Using the Simple Linear Regression:
MAD = 976.41
MSE = 1,439,943.32 
MAPE = 9%
Accuracy = 91%
  
# RECOMMENDATION
I recommend the Simple Linear Regression approach due to its 91% accuracy and error rate of 9%. which implies that anytime we use the Simple Linear Regression approach in the coming year 2022, there is going to be an error of 9% and a deviation of 976.41. Additionally, SLR has a superior performance in terms of MSE (Mean Squared Error), with a lower value of 1,439,943,32. A lower MSE value is desirable as it reflects a better model fit.
