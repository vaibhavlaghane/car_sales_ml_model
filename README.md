This Readme explains the intent and usage of this project 

The project uses pandas library and python as main technology .
sklearn library is imported  for various models like linearRegression , Ridge Regression etc.


This Data Science / ML project intends to process car sales related data set, infer the data, create ML models which can be used to predict the factor driving sales price of the car.
The Data set is analysed and formatted first to remove unwanted and erroneous factors.
The numerical and categorical data is also handled such that they can be used together for training the model.

The approach taken is to pick single parameter first and use liner Regression to observe the predictions. This may not be used for final analysis but is useful for knowledge purposes.
Since multiple features are involved , PolynomialFeatures, LinearRegression, Ridge Regression, Grid Search CV techniques are utilized.

The dataset is split into train and test data set and models are trained and values are predicted.
The Mean Sqaured Error and HyperParameter like alpha are calculated and fine tuned.

Different set of data/features are iterated through with various models.

SequentialFeatureSelector - helps find the best features to train on.
StandardScaler - helps to scale the parameters.

Also trying to obtain the coefficients:
Comparing Ridge regression model with that of a LinearRegression model built using 
SequentialFeatureSelector. Both of these approaches seek to limit the complexity of the model. 
The Ridge estimator applies a penalty that shrinks the coefficients of the model while using the 
SequentialFeatureSelector selects a subset of features to build a model with.

The model and features suggested are determined on minimum MSE and processing speed of the model and scalability


