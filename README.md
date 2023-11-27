Income Forecast
- Utilize advanced forecasting models to anticipate the total rolling income for the upcoming three months among personal customers. 

Data Source
- ODW

Table Names
- MISDATA.CUSTOMER
- MISDATA.ACCOUNT
- MISDATA_S1.SUM_RM_ACCOUNT_M01

Filters
- Only personal customer's
- Account status open
- GLCODEEXTERNAL is 13 or 22

Machine Learning Models
ARIMA (AutoRegressive Integrated Moving Average)
SARIMA (Seasonal AutoRegressive Integrated Moving Average)

Approach
- The approach involves aggregating the total rolling income for all customers over the past five years on a monthly basis. This grouped data is then subjected to various time series models, including ARIMA and SARIMA, to identify the most accurate fit. The model with the highest accuracy is selected to forecast the total rolling income for the next three months.
