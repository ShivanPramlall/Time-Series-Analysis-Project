# Time-Series-Analysis-Project
Time Series Analysis for GlobalMart to identify trends, seasonal patterns, and residual variations. Multiple forecasting models were implemented, including Holt-Winters (Additive Seasonality), AR, MA, ARIMA, and SARIMA, used to predict sales for the next year.

**Objective**
 

To analyze sales trends, identify seasonal patterns, and develop accurate time series forecasting models to predict future sales for GlobalMart.

 
**Exploratory Analysis**
(View GlobalMart Sales (Part I): Exploratory Data Analysis)
 

**Decomposition**

**Trend Component:** Sales remained stable initially but exhibited a clear upward trend starting around 2017, indicating business growth.

**Seasonality Component:** Strong periodic fluctuations suggest cyclical sales behavior at regular intervals.

**Residuals:** The residuals should ideally be white noise, but noticeable patterns indicate potential unexplained structure in the data.
 
**Forecasting Models & Evaluation**

To forecast future sales, multiple time series models were implemented and compared based on their Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

 
**Key Findings & Conclusion**

SARIMA was the best-performing model, achieving the lowest MAE and RMSE, making it the most suitable choice for forecasting future sales.
The identified trends and seasonal patterns can help optimize inventory, pricing, and marketing strategies.
