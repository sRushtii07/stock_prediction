# Stock Price Prediction (Google) with Linear Regression
This project aims to predict stock prices using linear regression and visualize the stock price trends for the Google (GOOGL) stock. The dataset used in this project is obtained from Kaggle, which includes historical stock prices for GOOGL. 

## Project Overview
The main components of the project are as follows:

* Dataset: The dataset contains historical stock price data for GOOGL, including the date and closing price.
* Data Preprocessing: The dataset is preprocessed to convert the 'Date' column to datetime format and set it as the index. 
* Splitting Data: The dataset is split into training and testing sets. In this project, 70% of the data is used for training the linear regression model, and the remaining 30% is used for testing.
* Linear Regression: A linear regression model is trained on the training data, using the 'Date' feature as the independent variable and the 'Close' price as the dependent variable.
* Prediction and Evaluation: The trained model is used to predict the stock prices for the testing data. The predicted prices are compared with the actual prices, and a DataFrame is created for visualization. Further, the actual and predicted prices are compared for the test dataset and the values of Mean Absolute error and Mean Squared Error is calculated.
* Visualization: The line graph is generated using Matplotlib and Seaborn libraries to visualize the actual and predicted stock prices. The graph displays the date on the x-axis and the closing price on the y-axis.

## Requirements
The following Python libraries are used in this project:

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn (sklearn)
These libraries must be installed in our Python environment to run the project.

## Usage
To use this project, follow these steps:

1. Download the GOOGL dataset from Kaggle and save it as a CSV file named 'GOOGL.csv'.
2. Install the required libraries mentioned in the 'Requirements' section.
3. Run the Python code provided in the project file.
4. The line graph of the stock price trends for GOOGL will be displayed, showing the actual and predicted stock prices.
