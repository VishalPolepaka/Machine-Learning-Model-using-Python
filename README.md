# Machine-Learning-Model-using-Python

## Overview:
This project aims to predict the aqueous solubility (LogS) of organic compounds using the Delaney dataset. By employing machine learning models such as Linear Regression and Random Forest Regressor, the project seeks to establish a reliable predictive framework for solubility estimation based on molecular descriptors.

## Dataset:
https://github.com/dataprofessor/data/blob/master/delaney_solubility_with_descriptors.csv

## Methodology:
### 1. Data Loading:
* Imported the dataset using pandas.
* Explored the dataset to understand its structure and contents.

### 2. Data Preparation:
* Handled missing values and ensured data consistency.
* Data seperation as x and y
* Split the dataset into training and testing sets.

### 3. Model Building:
* Implemented Linear Regression and Random Forest Regressor models using scikit-learn.
* Trained models on the training dataset and evaluated performance on the test set.

### 4. Model Evaluation:
* Assessed models using metrics such as Mean Squared Error (MSE) and R² score.
* Compared the performance of both models to determine the better predictor.

### 5. Data Visualization:
* Created scatter plots to visualize the relationship between predicted LogS values and experimental LogS values.
* Utilized matplotlib for plotting and numpy for numerical operations.

## Results:
### 1. Linear Regression:
* MSE: 1.020695
* R² Score: 0.789162

### 2. Random Forest Regressor:
* MSE: 1.407688
* R² Score: 0.709223
