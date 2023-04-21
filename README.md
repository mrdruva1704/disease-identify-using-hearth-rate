# disease-identify-using-hearth-rate

This code uses the scikit-learn library to train a decision tree classifier on heart rate data. The data is read in from a CSV file 'heart_rate_data.csv', which contains features related to heart rate and a binary classification label indicating whether the patient has a heart disease or not.

The data is first split into training and test sets using the train_test_split function from scikit-learn. The DecisionTreeClassifier is then used to fit the training data, and the accuracy of the classifier is evaluated on the test set using the accuracy_score function.

Finally, the code prints out the accuracy of the model and also prints out the 'Disease' column of the original data.
