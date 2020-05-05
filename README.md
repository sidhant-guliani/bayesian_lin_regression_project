# bayesian_lin_regression_project
bayesian analysis


##### Scikitlearn pointer
##### sklearn.linear_model.LogisticRegression vs sklearn.linear_model.LogisticRegressionCV
While the instance of the first class just trains logistic regression on provided data. The instance of the second class divides the Train dataset into different Train/Validation Set combinations before training and helps test the model is good across different splits of data. The process is called K-Fold Cross Validation (that’s where CV comes from) and is a very frequently used method in Machine Learning practice.
