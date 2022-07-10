# Temperature analysis
<h3> Motive </h3>
To forecast the upcoming monthly average temperature from whether dataset.
<h3> Process </h3>
1. Cleaning the data like removing null values, fixing the datatypes etc. <br>
2. EDA, analysing the seasonal patterns and outliers. <br>
3. Filtering the data as per the use e.g., Resampling & Removing outliers. <br>
4. Resampling as per different rules and analysing the different patterns after plotting all resamples. <br>
5. Checking the stationarity of data. <br>
6. Plotting acf and pacf charts for both non seasonal and seasonal data and analysing p,d,q as well as P,D,Q. <br>
7. Train test split our monthly resampled data. <br>
8. Applying Seasonal ARIMA or say SARIMAX, and plotting the results. <br>
9. Calculating R<sup>2</sup> score and residual means, which are as 0.98 and ~2.6°C <br>
10. Forecasting the data for next year end.
<h3> Conclusion </h3>
Seasonal Arima is able to predict the monthly average temperature with R<sup>2</sup> score nearly 98% which is pretty good. The error in predicted temperature on train data is around 2.6°.
