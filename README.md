# Flood-Prediction-Model--Monthly-Rainfall-Index-and-Flood-Probability
 the code performs the following steps:

Data Loading and Preprocessing:

Reads a CSV file into a pandas DataFrame (data).
Displays the top 5 rows of the DataFrame.
Checks for missing values in each column of the DataFrame.
Data Transformation:

Replaces categorical values in the 'FLOODS' column with numeric values.
Selects the feature data (x) and target variable (y) from the DataFrame.
Scales the feature data between 0 and 1 using Min-Max scaling.
Data Exploration:

Plots histograms of selected columns from the DataFrame.
Model Training and Evaluation:

Splits the data into training and testing sets.
Fits a logistic regression classifier to the training data.
Performs cross-validation on the classifier using the testing data.
Calculates and prints the mean accuracy score from cross-validation.
Predicts the target variable for the testing data.
Displays the predicted and actual values of the target variable.
Calculates and prints accuracy score, recall score, and ROC AUC score.
