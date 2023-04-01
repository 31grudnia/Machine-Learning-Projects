# Diabetes Prediction using Support Vector Machine model

Code is an implementation of a Support Vector Machine (SVM) model on the diabetes dataset to predict whether a person has diabetes or not.

First, the necessary libraries are imported, and the diabetes dataset is read using pandas. The dataset is then explored using various pandas functions such as head(), shape, describe(), value_counts(), and groupby().

The data is then split into input features (X) and labels (Y). The input features are then standardized using the StandardScaler function from the sklearn.preprocessing module.

Next, the data is split into training and testing sets using the train_test_split function from the sklearn.model_selection module.

An SVM model with a linear kernel is then created using the svm.SVC() function from the sklearn module. The model is trained on the training data using the fit() function.

The accuracy score of the model is then calculated for both the training and testing data using the accuracy_score function from the sklearn.metrics module.

Finally, a new input data point is created, which is then standardized using the same scaler used for the training data. The model is then used to predict whether the person has diabetes or not.

