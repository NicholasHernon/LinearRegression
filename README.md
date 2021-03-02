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

Screen Shot 2021-03-01 at 4.59.17 PM![image](https://user-images.githubusercontent.com/79678028/109575765-b33e4480-7aaf-11eb-9e8b-7ded5090d6f1.png)

