# Airline-Passnegers - Time Series Analysis and Forecasting
This repo aims to serve as a beginner friendly guide to various time series analysis, decomposition and forecasting techniques.

## Project Aims
* Analysis And Visualization Of The Airline Passengers Data
* Apply Data Decmposition Techniques
* Apply Different Forecasting Techniques And Comment On each Technique Whether It Should Be Used Or Not And Under What Conditions
* Evaluate Different Forecasting Techinques Using Fixed Partitioning, Roll-Forward Partitioning, Cross-Validation

## Data
The Data Used Can Be Found [Here](https://www.kaggle.com/datasets/gauravduttakiit/airline-passenger-traffic). The Data Contains Monthly Data Of Airline Passengers From 1949-01
To 1960-12. The Below Is A Visualization of The Data:
<p align="center">
  <img src="https://github.com/mkldhz/Airline-Passnegers---Time-Series-Analysis-and-Forecasting/assets/61518213/c30ca90e-da87-4508-81ce-a741e64df008"/>
</p>

## Techniques Covered
1 - Simple Moving Average

2 - Naïve Forecasting

3 - Weighted Moving Average

4 - Simple Linear Regression

5 - Classical Decomposition

6 - STL

7-1 Arima

7-2 S-ARIMA

8-1 Single Exponential Smoothing

8-2 Double Exponential Smoothing

8-3 Triple Exponential Smoothing

9 - Facebook Prophet Algorithm

10 - Supervised Machine Learning (XGBoost)

## Results
The evaluation metric used is RMSE and each techniques is evaluated using fixed partitioning, roll-forward partitioning, cross-validation. Below are the results of all the forecasting techniques used in the project:

| Technique                            | Fixed  | Roll Forward | Cross Validation |
|--------------------------------------|--------|--------------|------------------|
| Simple Moving Average                | 113.8  | 55.38        | 139.60           |
| Naïve Forecasting                    | 137.3  | 44.20        | 142.60           |
| Weighted Moving Average              | 84.6   | 52.40        | 183.00           |
| Linear Regression                    | 74.7   | 55.40        | 80.00            |
| Classical Decomp.                    | 60.0   | 54.70        | 84.10            |
| STL Decomp.                          | 68.7   | 66.20        | 80.70            |
| ARIMA                                | 126.1  | 39.72        | 141.83           |
| S-ARIMA                              | 39.9   | 11.50        | 55.10            |
| Single Exp. Smoothing                | 139.7  | 47.10        | 140.30           |
| Double Additive Exp. Smoothing       | 118.3  | 44.00        | 93.70            |
| Double Multiplicative Exp. Smoothing | 107.60 | 43.70        | 104.90           |
| Triple Additive Exp. Smoothing       | 35.70  | 12.30        | 57.40            |
| Triple Multiplicative Exp. Smoothing | 13.80  | 10.30        | 40.10            |
| Facebook Prophet                     | 40.3   | 31.50        | 45.40            |
| XGBoost Regressor                    | 53.1   | NaN          | 104.20           |



