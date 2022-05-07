# Logistic Regression 

Logistic regression is a process of modeling the probability of a discrete outcome given an input variable. The most common logistic regression models a binary outcome; something that can take two values such as true/false, yes/no, and so on.


### Dataset 1: 

'FEV.cvs'

1. Age 

2. Hgt

3. FEV

4. Smoke (dummy)

5. Sex (dummy)

    I set X = df[['Age', 'FEV','Hgt']] and y = df['Smoke']
    

### Dataset 2:

dataDict={'time':list(np.arange(0.50,5.50,0.25)),
        'no or yes':[0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 1, 1, 1, 1, 1, 1, 1, 1, 1]}

### Tasks: 


1. exlporing the dataset 

2. visualizing the dataset: 
    
    jointplot
    
    scatter plot
    
    distplot
    
    plot all of the columns 
    
    pairplot
    
3. testing accuracy 

4. test and training set

5. obtaining ROC curve


```python

```
