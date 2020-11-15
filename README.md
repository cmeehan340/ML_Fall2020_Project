# Classifiying Car Prices
## Chris Meehan
## 11/15/2020
## COMP740 Machine Learning - Fall 2020

Original Data Source: https://www.kaggle.com/austinreese/craigslist-carstrucks-data

```project_data.ipynb``` contains data cleanup as well as visualization 

```project_classication.ipynb``` contains encoding values, scaling values, splitting of the data, and training and testing.  


The goal of this project is to be able to classify the value of a car, new or used, based off of craigslist car sales data.  The input would be a car with make, model, condition, number of cylinders, fuel type, odometer reading, title status, transmission type, drivetrain, and paint color.  With these features I have built a model that can predict the value of a car.  The original data needed a significiant amount of cleaning before it would give good results. I started by removing na values and then going through each column to figure out data outlyers and remove them to give the model a much easier time in making a prediction.  This would be useful to anyone trying to sell their vehicle on either craigslist or facebook marketplace and wanted to get an estimated value.  Websites like https://www.kbb.com/ and https://www.nada.com/ have similar functionality.  