Income Forecast
- Use forecast model to predict total rolling income for next 3 month for personal customers.

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
- ARIMA
- SARIMA

Approach
- All the customer's total rolling income(last 5 years) is grouped on monthly level. The grouped data is later passed to different time series models to best fit the data. Based on accuracy best model is picked to predict next 3 months total rolling income.
