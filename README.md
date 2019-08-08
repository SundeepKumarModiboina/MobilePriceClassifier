# MobilePriceClassifier
Making use of Scaling and Normalizing the data before modelling


Before fitting the data with some models, we are scaling and normalizing the data.

The dependent variable has 4 unique values 0,1,2 and 3.

There are 20 features and i am taking the top 10 features by their importances.
The feature importance is calculated using ExtraTreesClassifier feature importances.

Using the model Decision Tree Classifier and SVM along with Grid Search CV.
