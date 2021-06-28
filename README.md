# Titanic
Machine learning exercise with Python to predict survivors

Reference:  https://www.kaggle.com/c/titanic/

## Notable tasks

**Deal with missing data**   
* mean for missing 'Pclass' values   
* Imputation function for missing 'Age' values   

**Convert categorical features to dummy variables**   

## Model prediction - Logistic regression
Used Scikit Learn   

### Model 1
* No data normalisation   
* Used default values (C = 1)   

### Model 2
* Normalised data using MinMaxScaler   

### Model 3
* Removed data normalisation   
* C = 0.1 (default = 1) ---> Smaller values of C represent strong regularisation   

### Model 4
* C = 5   

### Model 5
* C = 10   

## Model prediction - K Nearest Neighbors
Used Scikit Learn   

### Model 1
* K = 1

### Model 2
* Plotted K vs Error Rate for K = 1,2,3...40   
* Chose, K = 15
