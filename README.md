# airline_fare_prediction
### Prediction of airline fare using regression model Random Forest and other Python libraries
> Features in dataset include Airline, Source, Destination, Route, Departure and Arrival Time, Number of Stops and Price
* Use of pandas and sea-born to pre-process data:
  * Conversion of columns into DateTime and handling missing values
  * Taking care of the categorical values using encoding
  * Conversion of columns into integers and into a format for efficiency of ML model
  * Detecting outliers and dealing with it
* Analysing prices of ticket with other features by creating plots
* Determined the features which had the most impact by feature selection technique
* Created a python function to create a baseline Random Forest model along with printing it's score using various metrics
* Established a pickle file to re-use the model created, in the same function
* Trained the data with other Regression models to find the best one
* Tuned the model using RandomizedSearchCV and cross validation to find the best hyperparameters
