# House Price Prediction using XGBoost Regression model

The code load the California housing dataset using the fetch_california_housing function from scikit-learn. It then converts the dataset to a Pandas dataframe, adds the target variable 'Price' to the dataframe, and checks for null values. It then splits the data into training and testing sets using the train_test_split function from scikit-learn.

The code then loads an XGBoost regression model, trains the model on the training set, and computes R-squared and mean absolute error scores for the training set. It then plots a scatter plot of actual prices vs predicted prices for the training set. The code then computes R-squared and mean absolute error scores for the testing set and prints them to the console.
