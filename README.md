# Project 2 - Ames Housing Data Pricing Prediction

## Building a Home Valuation Model
Automated valuation models are helpful tools for everyday people to use to closely estimate the value of their home or value of a desired home. Soon-to-be home buyers and sellers want to ensure they are in a fair value deal, and using online valuation tools, like the one here from [Remax](https://www.remax.com/home-value-estimates), helps with that process. The tool in this example for Remax likely aggregates the most recent housing data and uses the data to predict the price of the home today. However, these tools are inherently imperfect as different machine learning tools have different levels of accuracy.

## Data
In this project, the valuation model is based on the Ames housing dataset provided through this [Kaggle Challenge](https://www.kaggle.com/t/2dde5663e03b4165b853ff65e723c26d).

## Modelling
The scores of the following regression models will be compared to both find the optimal score and learn how different tools impact model performance.

- Linear Regression
- Ridge
- Lasso
- Random Forest Regressor
- AdaBoost with Decision Tree Regressor
- Support Vector Machine Regressor


## Code
```
|__ code
|   |__ 01_EDA_and_Cleaning.ipynb   
|   |__ 02_Pipeline_and_Model.ipynb   
|   |__ 03_Insights_and_Conclusions.ipynb
```

## Data Dictionary



## Data Files

```
|__ data
|   |__ train.csv #original data from Kaggle
|   |__ test.csv #original data from Kaggle
|   |__ ames_clean.csv
|   |__ X_test.csv
|   |__ X_train.csv
|   |__ X_test.csv
|   |__ y_train.csv
|   |__ y_test.csv
|__ images
```
## Data Files
```
SAVE EDA AS IMAGES
|   |__ coefficients.png
|   |__ neighborhoods.png
|   |__ predictions.png
|__ presentation.pdf
|__ README.md
```






