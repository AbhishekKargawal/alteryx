Income Forecasting Overview

Utilize advanced forecasting models to anticipate the total rolling income for the upcoming three months among personal customers. The data, drawn from the ODW with tables such as MISDATA.CUSTOMER, MISDATA.ACCOUNT, and MISDATA_S1.SUM_RM_ACCOUNT_M01, is refined through specific filters. These filters include isolating personal customers, ensuring an open account status, and focusing on GLCODEEXTERNAL values of 13 or 22.

Time Series Models Employed

ARIMA (AutoRegressive Integrated Moving Average)
SARIMA (Seasonal AutoRegressive Integrated Moving Average)
Approach

The approach involves aggregating the total rolling income for all customers over the past five years on a monthly basis. This grouped data is then subjected to various time series models, including ARIMA and SARIMA, to identify the most accurate fit. The model with the highest accuracy is selected to forecast the total rolling income for the next three months.
