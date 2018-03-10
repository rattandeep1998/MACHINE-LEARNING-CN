## PCA (PRINCIPAL COMPONENT ANALYSIS) ##

### SVM Continued Discussion ###

* Large Margin Classifier
* Kernel Trick
	* Landmark points
* Optimisations in SVM
	* M matrix add karna
* Deciding value of kernel, c(regularisation) and gamma.

#### Grid Search CV ####

* present in sklearn
Picks up best combination out of all possible combination of values
* Takes either single dictionary (c,gamma) or list of dictionaries (with different kernels).
* Use of best_estimator_


### PCA ###

Reducing dimensionality (or indirectly we can say reducing number of features)

We were reducing features using :-
* Filtering on our own of the required/significant features
* Feature selection 

In PCA, we are reducing dimensions.

2 dimension ----> 1 dimension

Then,
* Find rotated dimension from the 2 dimensions given (or 2 features given)
* Out of these 2 dimensions keep the one that gives more information about the data points

We pick up principal components joh maximum best represent kar rahe hain data ko.

Vector representation of the dimensions.

#### Using PCA ####

On breast cancer dataset

* Accuracy decreases
* Time will considerably decrease -- added advantage of PCA when there are large number of features

ZERO MEAN DATA

Random Forest Classifier 

* With PCA
* Without PCA

#### Sklearn liblinear -- EIG ####

* Eigen Values - kis dimension se kitni variance explain ho rahi hai
* Eigen Vactors - eigen vector values of dimensions

#### Code for PCA from scratch ####

* Generating mean data ourself
* 3D representaion library
* Transformed into lower dimensions 
	* Points transformed -- using eigen vectors
	* Top k dimensions picked -- using eigen values

#### Sklearn inbuilt PCA used ####

#### Inverse transform ####

* Gaining back the dimensions 
* Obtained data will be like the original data but not exactly the same.


Data Sets used : BREAST CANCER DATASET, SELF GENERATED MEAN VALUES DATA :+1: 

:smiley: