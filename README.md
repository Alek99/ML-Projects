# ML-Projects Aleksander Petuskey

# Project 1 Credit Card Fraud Detection
Anonymized credit card transactions labeled as fraudulent or genuine.

Data Set Information:
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Project 2 Iris Data Set 
Predicted attribute: class of iris plant. 

Data Set Information:
This is perhaps the best known database to be found in the pattern recognition literature. Fisher's paper is a classic in the field and is referenced frequently to this day. The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other. 

Attribute Information:

1. sepal length in cm 
2. sepal width in cm 
3. petal length in cm 
4. petal width in cm 
5. class: 
-- Iris Setosa 
-- Iris Versicolour 
-- Iris Virginica


![alt text](https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwi9ooGklLzmAhULsJ4KHdyoBWsQjRx6BAgBEAQ&url=http%3A%2F%2Fwww.chicagonow.com%2Fchicago-garden%2F2009%2F05%2Fblooming-in-my-garden-52709%2F&psig=AOvVaw37-EV0lp6bYf4tI-9Myx5E&ust=1576654030451525)

# Project 3 Income Prediction
Prediction task is to determine whether a person makes over 50K a year. 

Data Set Information:
Extraction was done by Barry Becker from the 1994 Census database. A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0)) 

Attribute Information:

Listing of attributes: 

>50K, <=50K. 

age: continuous. 
workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked. 
fnlwgt: continuous. 
education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool. 
education-num: continuous. 
marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse. 
occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces. 
relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried. 
race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black. 
sex: Female, Male. 
capital-gain: continuous. 
capital-loss: continuous. 
hours-per-week: continuous. 
native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.


# Project 4 Breast Cancer Wisconsin (Original) Data Set 
Predicting the probability that a diagnosed breast cancer case is malignant or benign based on Wisconsin dataset from UCI repository.

Data Set Information:
Samples arrive periodically as Dr. Wolberg reports his clinical cases. The database therefore reflects this chronological grouping of the data. This grouping information appears immediately below, having been removed from the data itself: 

Group 1 367 instances (January 1989) 
Group 2 70 instances (October 1989) 
Group 3 31 instances (February 1990) 
Group 4 17 instances (April 1990) 
Group 5 48 instances (August 1990) 
Group 6 49 instances (Updated January 1991) 
Group 7 31 instances (June 1991) 
Group 8 86 instances (November 1991) 
----------------------------------------- 
Total: 699 points (as of the donated datbase on 15 July 1992) 

Attribute Information:

1. Sample code number: id number 
2. Clump Thickness: 1 - 10 
3. Uniformity of Cell Size: 1 - 10 
4. Uniformity of Cell Shape: 1 - 10 
5. Marginal Adhesion: 1 - 10 
6. Single Epithelial Cell Size: 1 - 10 
7. Bare Nuclei: 1 - 10 
8. Bland Chromatin: 1 - 10 
9. Normal Nucleoli: 1 - 10 
10. Mitoses: 1 - 10 
11. Class: (2 for benign, 4 for malignant)

# Project 5 Solar Flare Data Set 
Data Set Information:

Notes: 
-- The database contains 3 potential classes, one for the number of times a certain type of solar flare occured in a 24 hour period. 
-- Each instance represents captured features for 1 active region on the sun. 
-- The data are divided into two sections. The second section (flare.data2) has had much more error correction applied to the it, and has consequently been treated as more reliable.


Attribute Information:

1. Code for class (modified Zurich class) (A,B,C,D,E,F,H) 
2. Code for largest spot size (X,R,S,A,H,K) 
3. Code for spot distribution (X,O,I,C) 
4. Activity (1 = reduced, 2 = unchanged) 
5. Evolution (1 = decay, 2 = no growth, 3 = growth) 
6. Previous 24 hour flare activity code (1 = nothing as big as an M1, 2 = one M1, 3 = more activity than one M1) 
7. Historically-complex (1 = Yes, 2 = No) 
8. Did region become historically complex on this pass across the sun's disk (1 = yes, 2 = no) 
9. Area (1 = small, 2 = large) 
10. Area of the largest spot (1 = <=5, 2 = >5) 

From all these predictors three classes of flares are predicted, which are represented in the last three columns. 

11. C-class flares production by this region in the following 24 hours (common flares); Number 
12. M-class flares production by this region in the following 24 hours (moderate flares); Number 
13. X-class flares production by this region in the following 24 hours (severe flares); Number 


