# Predicting-House-Prices
### Introduction
Each house has a variable price and depends on the features of the property owned, the area of the house to the size of the house. Currently, this project focuses on predicting home prices using an end-to-end approach of various models from machine learning and involving the Flask API for the prediction process in the local terminal command prompt

### Understanding All Features of Dataset
| Variable          | Description                                                |
|-------------------|------------------------------------------------------------|
| Price (in Rupees) | House prices in rupees                                     |
| location          | home location in India                                     |
| Carpet Area       | Carpet width measurement in sqft units                     |
| Transaction       | Types of transactions                                      |
| Furnishing        | Categories of Home Furnishings                             |   
| facing            | Front of the house                                         |
| overlooking       | The house faces directly                                   |
| Society           | community around the house                                 |
| Bathroom          | Lots of bathrooms                                          |
| Balcony           | Lots of balcony                                            |
| Car Parking       | conditions and amount of car parking                       |
| Super Area        | Strategic location of the house                            |                                         
### Project Scope
This project includes exploratory data analysis to find the distribution of data to correlation with the Price House feature as well as testing data by conducting various approaches such as the Least Angel Regression model, Linear Regression and Gradient Boosting Regressor models and the evaluation metrics used are Mean Absolute Error, Mean Squared Error and R-Squared. Meanwhile, the deployment process uses the Django API which functions to run predictions locally or in the CMD terminal.

### How to use predictions???
Make sure the library you are using is installed in the Anaconda environment.
If the above point is ready, the next step to do is to open the Anaconda Prompt terminal and navigate to the path folder containing all the files of this project then run 'pyhton testing_deploy.py'. next go to the latest anaconda prompt page and make sure the path has gone to the path of the project file folder and run 'curl -X POST http://127.0.0.1:5000/predict -H "Content-Type: application/json" -d @data.json'
