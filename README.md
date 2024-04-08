## Project Objective
#### In this project, we are asked to combine historical usage patterns with weather data in order to 
#### predict bike rental demand,target is to predict the count of bikers.Two datasets are given train and test Data.
#### training part is done on train dataset and the model is saved.The predicting of result is done on the test dataset.

### Methodology
### EDA
#### Performed EDA to get more informative features like null values,outliers,correlation and other features.

### Model Bulding
#### Linear Regression Model
#### DecisionTree Regressor Model
#### Randomforest Regressor Model

### Model Validation
#### Root Mean Squared Logarithmic Error (RMSLE)

## Solution Plan
### Train Data
#### First of all the train dataset is imported with all the necessary packages. Data is checked for the basic details of the train dataset. 
#### EDA is conducted to gather information about the relation between the columns of the dataset which helps in the selection of the model.
#### Here the EDA helped in selecting the Multiple Linear Regression Model. After model selection,the model is built using the scikit-module.
#### The coding is done in modularised format.The data is split into 80:20 format to train and test.The model predicted an r2_score or co-efficient of determination as 1.
#### The accuracy of the model is 100%.The Root Mean Squared Logarithmic Error of this model is 0.0.

## Test data
#### The saved model is used to predict the test data.



