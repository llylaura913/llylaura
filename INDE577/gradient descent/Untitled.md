# Gradient Descent

Gradient descent (GD) is an iterative first-order optimisation algorithm used to find a local minimum/maximum of a given function.

### 1. Batch Gradient Descent

In Batch Gradient Descent, all the training data is taken into consideration to take a single step. We take the average of the gradients of all the training examples and then use that mean gradient to update our parameters. So that’s just one step of gradient descent in one epoch.

### 2. Stochastic Gradient Descent

Stochastic Gradient Descent just picks a random instance in the training set at every step and computes the gradients based only on that single instance.

### 3. Mini-batch Gradient Descent

Mini- batch GD computes the gradients on small random sets of instances: Neither we use all the dataset all at once nor we use the single example at a time. We use a batch of a fixed number of training examples which is less than the actual dataset and call it a mini-batch.



### Tasks: 

1. implement Batch Gradient Descent, and check theta

2. implement Stochastic Gradient Descent, and check theta

3. implement Mini-batch Gradient Descent, , and check theta

4. plotting avg_cost vs. Epoch curve 

5. By changing learning rate, we see how theta will change




```python

```
