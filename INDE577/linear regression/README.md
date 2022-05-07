# Linear Regression 

### Dataset: 

'FEV.CVS'

. Age 

. Hgt

. Smoke 

. Sex 

. FEV

### Task: 

1. building simple linear model: y_hat = bo + b1*X1

2. building multiple linear model: y_hat = bo + b1X1 + b2X2 + b3*X3 ......+ε

3. exploring their corrleation: constructing correlation heat map 

4. computing MSE, RMSE, MAE, and R_squared for the models.

### Method: 

When we have training and testing datasets, we’ll apply a machine-learning linear regression algorithm to predict the values:

    The data we use is usually split into training data and test data. The training set contains a known output and the model learns on this data in order to be generalized to other data later on. We have the test dataset (or subset) in order to test our model’s prediction on this subset.

1. using a couple of libraries: sklearn.model_selection to split the training and testing dataset, and matplotlib to draw the regression line.

2. Since we’ve split our data into x and y, now we can pass them into the train_test_split() function as a parameter along with test_size, and this function will return us four variables. They’re x_train, y_train, x_test, and y_test.

3. if we pass test_size=0.2, then it means we want to keep 20% of the data of the entire dataset for the testing purposes.


```python

```
