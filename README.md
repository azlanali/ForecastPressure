# ForecastPressure
Forecasting Annulus Pressure

Created Annulus Pressure Excel forecast to check the possibility of developing a better forecasting using R.

sheet data: you can populate all your well name and enter the data columwise, you need to have 21 (Sheet data: column B to V) and you can check the model against the actual colum W to column AB.  data point - to have good  data.

in the sheet forecast, there is a dropdown cell b3, it refers to the sheet data to get the data, so if you choose xx1234, it will call the data and populated in the preformated table below. row 32-37 is used by the excel function to forecast the pressure based on the 21 data point using  ETS algorithm
