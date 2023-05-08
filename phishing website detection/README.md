# PHISHCOOP -- Phishing Website Detection
Detection of phishing websites is a really important safety measure for most of the online platforms. So, as to save a platform with malicious requests from such websites, it is important to have a robust phishing detection system in place.

## DATA SELECTION

The dataset is downloaded from UCI machine learning repository. The dataset contains 31 columns, with 30 features and 1 target. The dataset has 6992 observations.

## MODELS

To fit the models over the dataset the dataset is split into training and testing sets. The split ratio is 75-25.  Where in 75% accounts to training set. 

Now the training set is used to train the classifier. The classifiers chosen are:  
#### * Logistic Regression
#### * Decision Tree
#### * KNN
#### * Random Forest Classification
#### * Support Vector Machine

We will see which one fits best in our dataset.

### 1.Logistic Regression

Fitting logistic regression and creating confusion matrix of predicted values and real values I was able to get 92.4 accuracy. Which was good for a logistic regression model.

### 2.Support Vector Machine

Support vector machine with a rbf kernel and using gridsearchcv to predict best parameters for svm was a really good choice, and fitting the model with predicted best parameters I was able to get 96.5 accuracy which is pretty good.

### 3.Decision Tree

Decision Tree machine using gridsearchcv to predict best parameters for decision tree, and fitting the model with predicted best parameters I was able to get 92.5 accuracy.

### 5.KNN

K-nearest neighbour machine using creating confusion matrix of predicted values, I was able to get 95.7 accuracy.

### 5.Random Forest Classification

Next model I wanted to try was random forest and I will also get features importances using it, again using gridsearchcv to get best parameters and fitting best parameters to it I got very good accuracy 97.6.

Random forest was giving very good accuracy. We can also try artificial neural network to get a improved accuracy.