# Ride-Time-Analysis

The  data  for  this  project  has  been  extracted  from  the  dataset "Uber Daily TravelTimes 18 Cities 2016-2020" on Kaggle, while the weather data has been extracted from a London-based weather station dataset on Meteostat.This dataset contains the mean travel time (in seconds) of Uber rides from the center-most area in London to all other areas, together with information on weather conditions(temperature, precipitation and wind speeds) from a weather station in London.  Information is provided for  almost  2  years,  from  2nd  January  2016  to  31st  December  2017.   The description of the variables is available below.
 
Description of the variables:
  
  
Date                  | Date (yyyy-mm-dd)


MeanTravelTimeSeconds |  Mean travel time (seconds)


tavg                  | Average temperature (°C)


tmin                  | Minimum temperature (°C)


tmax                  | Maximum temperature (°C)


prcp                  | Total precipitation (mm)


windspeed             | Wind speed (0:  low; 1:  medium; 2:  strong winds)

The dataset is available in the file uberLondon.csv.  We use R to analyse the dataset and address the following tasks:
(1) Split the data into train and test sets.
(2) Analyse the training set, produce summary statistics. Check for outliers, missing values and relationships between the variables
(3) Clean the dataset and fit statistical models to the training data and use them to produce a forecast.
(4) Choose the best model based on RMSE scores and other performance metrics.
