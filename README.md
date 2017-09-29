# LinearRegression-Multiple-variables
Data Science-Linear Regression with Multiple variables


I have implemented linear regression with multiple variables to predict the prices of houses.

The ﬁle ex1data2.txt contains a training set of housing prices in a city. The ﬁrst column is the size of the house (in square feet), the second column is the number of bedrooms, and the third column is the price of the house.

Feature Normalization

By looking at the data values, note that house sizes are about 1000 times the number of bedrooms. When features diﬀer by orders of magnitude, ﬁrst performing feature scaling can make gradient descent converge much more quickly.

I have to  featureNormalize for that:

-Subtract the mean value of each feature from the dataset.

-After subtracting the mean, additionally scale (divide) the feature values by their respective “standard deviations.”

Gradient Descent:

I have implemented gradient descent on a Multivariate regression problem. Now there will be more features in the Matrix.

Selecting learning rates:

In this part, I will get to try out diﬀerent learning rates for the dataset and ﬁnd a learning rate that converges quickly. 
Run gradient descent for about 50 iterations at the chosen learning rate. After the last iteration, implement the script that plots the J values against the number of the iterations.

