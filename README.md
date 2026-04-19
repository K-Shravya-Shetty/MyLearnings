# **Linear Regression**
Linear Regression is a simple statistical and machine learning method to understand and predict the relationship between the variables.

## Types of Linear Regression 
1.Simple Linear Regression : This has one input variable.
2.Multiple Linear Regression :  This has more than one input variables.

**Features** : Features are the input variables or the datapoints used by the model tolo make predictions or decisions.

**Lables** : Labels are the final values you want the machine learning model to predict.
### *Types of lables* 
1. Continuous Lables (Regression) : Used when the output is a number.
2. Categorical Lables (Classification) : Used when output is a category.
3. Binary Lables : Only 2 possible values.

**Weights** : Weights are numbers that tell the model how important each feature is when making prediction.

**Bias** : The bias is a extra number added to the final prediction which allows the line to shift up or down. It is like an adjustment factor helping the model fit the data better but not forcing it to go through the origin.

**Learning Rate** :  The learning rate o=controls how quicly the model's weigths and bias change during the training. Learning rate controls how fast or how slow a model learns. When learning rate is high the model tends to learn fast but it can be unstable and also lead to bad learning because the model may inherit or learn wrong or not so usefull stuff. When the learning rate is slow the model will learn slower but it is more steady and stables learning.

**Batches** : Large datasets is often broken down into smaller groups called batches.This helps making training faster and sometimes more accurate.

**Epoch** An epoch is simply one complete pas over the entire dataset. Everytime the model see all the data and adjusts its weights and bias, that counts to one epoch.

**Cost Function** :  A cost functionis a mathematical formula that tells us how far off the model's predictions are from the actual results. If the result of the cost function is small then the model is predictin well. If the result of the cost function is big then model is not predicting well.

**Loss** : Loss measures the mistake the model makes for ine preduction. For example if your model predicts the price of one house as 20000 but the actual price is 25000 the loss tells you the difference, It's like checking each guess individually. The cost function is average of these losses over all data points.

**Gradient Descent** : Gradient descent is an optimization algorithm used to reduce the error of the machine learning model by gradually adjusting the parameters.
###Types of Gradient Descents : 
1.Batch Gradient Descent : Uses entire data set to calculate the gradient.
2.Stochastic Gradient Descent  : Uses one data point at a time to calculate.
3.Mini Batch Gradient Descent : Uses small batches of data to calculate gradient.

**Line of best fit** : The line of best fit is a straight line that gets closer to all the data ponts. 

**Mean Squared Error** : It is the average of the squared difference between the predicted values and the actual values.

$$MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2$$

**Mean Absolute Error** : MAE is the average of the absolute difference between the predicted and the actual value.

$$MAE = \frac{1}{n} \sum_{i=1}^{n} |y_i - \hat{y}_i|$$








