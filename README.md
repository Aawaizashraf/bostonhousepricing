
# Boston House Price Prediction - Deployed using Flask

## Overview

The aim of this project is to build a machine learning model that predicts the median value of owner-occupied homes in various neighborhoods in Boston, and deploy it using Flask as a web-based application. The data used in this project was collected in 1978 and contains information on 506 neighborhoods in the Boston area.

## Data

The data used in this project was obtained from the UCI Machine Learning Repository and consists of 13 features for each neighborhood, including:

* CRIM: per capita crime rate by town
* ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
* INDUS: proportion of non-retail business acres per town
* CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
* NOX: nitric oxides concentration (parts per 10 million)
* RM: average number of rooms per dwelling
* AGE: proportion of owner-occupied units built prior to 1940
* DIS: weighted distances to five Boston employment centers
* RAD: index of accessibility to radial highways
* TAX: full-value property-tax rate per $10,000
* PTRATIO: pupil-teacher ratio by town
* B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
* LSTAT: % lower status of the population

## Requirements

The following packages are required to run this project:

* NumPy
* Pandas
* Os
* Matplotlib
* Seaborn
* Scikit-learn
* Pickle
* Flask

## Usage

To use this project, follow these steps:

* Clone the repository to your local machine
* Install the required packages using pip or conda
* Run the flask application using the command flask run in the terminal
* The application will be available at http://localhost:5000/
* Enter the feature values for a neighborhood and submit the form to get the predicted median value of owner-occupied homes.

## Conclusion

This project demonstrates the deployment of a machine learning model using Flask. The model, predicts the median value of owner-occupied homes in various neighborhoods in Boston. The application is a simple web-based interface that can be used to predict the median value of owner-occupied homes based on the input features. The model's performance can be improved by exploring other algorithms and incorporating additional features in the data.
