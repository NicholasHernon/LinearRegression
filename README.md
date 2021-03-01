# Linear regression model to predict house prices

This notebook creates a linear regression model to predict house prices. The dataset used for this notebook is the Ames Housing dataset, which was compiled for data science by Dean De Cock.

The dataset consists of 1,460 rows and 81 columns.

SalePrice is the dependent variable for the regression model. After determining the correlation coefficient between independent variables in the dataset and SalePrice, 5 independent variables were selected for the model:

* OverallQual - Overall Quality
* GrLivArea - Above Ground Living Area
* GarageArea - Garage Area
* TotalBsmtSF - Total Basement Square Feet
* YearBuilt - Construction Year

After splitting the data into training and test datasets, sklearn.linear_model.LinearRegression is used to fit a linear model.

The model achieved an R squared value of 0.838.
