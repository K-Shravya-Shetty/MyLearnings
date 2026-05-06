# Linear Regression :

Linear Regression is a simple statistical and machine learning method to understand and predict the relationship between the variables.

# Types of Linear Regression

1.Simple Linear Regression : This has only one input variable.
2.Multiple Linear Regression : This has more than one input variable.

# Features

Features are input variables or the datapoints used by the model tolo make predictions or decisions.

# Lables

Labels are the final values you want the machine learning model to predict.

# Types of Labels

1.Continuous labels (regression) : Used when output is a number.
2.Categorical labels (Classification) : used when output is category.
3.Binary labels : Only 2 possible values.

# Weights

Weights are numbers that tell the model how important each feature is when making the prediction.

# Bias

The bias is an extra number added to the final prediction, which allows the line to shift up or down. It is like an adjusting factor helping the model fit the data better by not forcing it to go through the orgin.

# Learning Rate

The learning rate controls how quickly the model weights and bias change during the training. Learning rate cotrols how fast or how slow the model learns.Whe learning rate is high the model tend to learn fast but it can be unstable and aslo lead to bad learning because the model maay inherit or learn wrong ot not so useful stuff. When the learning rate is low the model will learn slower but it is more steady and stable learning.

# Batches

Large datasets, is often broken down to smaller groups called batches. This helps making training faster and sometimes more accurate.

# Epoch

An epoch is simply one complete pass over the entire dataset. Everytime the model see all the data and adjust its weights and bias and that counts as an epoch.

# Cost Function

A cost function is a mathematical formula that tells us how far off the model's predictions are from the actual results.If the result of the cost function is small then the model is predicting well.If the result of the cost function is large then the model is not predicting well.

# Loss

Loss measures the mistake the model makes for one predictions.For example if the model predicts the price of the house as 20k but the actual price is 25k the loss tells you the difference. Its like checking each guess individually.

# Gradient Descent

Gradient descent is an optimization algorithm used to reduce the error (loss/cost) of the machine learning model by gradualy adjusting its parameters.

# Types of gradient descent

1.Batch gradient descent - use entire data set to calculate the gradient. 2. Stochastic gradient descent - Use some data points at a time to calculate the gradient.
3.Mini batch gradient descent - Uses small batches of data to calculate gradient .

# Line of best fit

The line of best fit is a straight line thatgets closest to all the data points.

# Mean Squred Error ( MSE )

$$MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2$$
It is the average of the squared difference between the predicted value and the actual value.

# Mean Absolute Error ( MAE )

$$MAE = \frac{1}{n} \sum_{i=1}^{n} |y_i - \hat{y}_i|$$
Mae is the average of the absolute difference between the predicted value and the actual value.
