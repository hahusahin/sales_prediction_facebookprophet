# Rossmann Sales Prediction using Facebook Prophet

### Goal
To predict future daily sales of Rossmann Stores given the historical sales data of its Stores using Facebook Prophet framework.

### Data Description
* We have two dataset for this study, one for Sales (the transactions recorded per day) and one for the Stores (information about the unique 1115 stores).

* Data Source: https://www.kaggle.com/c/rossmann-store-sales/data

### Exploratory Data Analysis - Modeling
* Missing values are detected and filled

* The two dataset (sales data and Stores data) is merged 

* Relationship between target variable (sales) and the features are examined and some observations are made

* As a model Facebook Prophet is used. I define a function that tooks:
   * The id of the store that we want to predict
   * Our final merged dataset
   * State and School holidays (in an applicable format to this framework)
   * How many days we want to predict

And then plots the related components that we can interpret.

### Libraries Used
* pandas, numpy
* matplotlib, seaborn
* facebookprophet
