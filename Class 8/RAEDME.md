## KNN (K-Nearest Neighbors) ##

### Multinomial Logistic Regression ###
* Formula for finding probability estimates
* Taking intercept (coefficient to be 1) into consideration

### Stochastic & Batch Gradient Descent ###
* different solvers used - simple, newton, etc.
* documentation - sklearn

#### Logistic Regression (sklearn) on Breast Cancer Dataset ####


### KNN ###

* Fit function
	* Does nothing - only saves training data

* Predict Function
	* Finds distance of current tesing point from all the training points
	* Sort all the distances
	* Pick up lowest k values (nearest k data points)
	* For the current testing points, predict the class which is given by majority out of these k points.

#### Problem with KNN ####

TRAINING TIME is very less whereas TESTING TIME is very huge, which practically should not be the case with any model.

#### Self implementation of KNN ####
* Predict function
* Graph plot - cross validation score v/s Value of K


Link for plotting decision boundaries in KNN :
http://scikit-learn.org/stable/auto_examples/neighbors/plot_classification.html

Data Sets used : Breast Cancer :+1: 

:smiley: