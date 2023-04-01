# Loan Status Prediction using Support Vector Machine model

This code is an example of using the **SVM** algorithm to build a loan approval prediction model.

First, the necessary packages are imported, including **numpy, pandas, seaborn, sklearn, and svm**. Then the loan dataset is loaded into the Jupyter notebook and converted into a pandas dataframe.

Next, some exploratory data analysis is performed, including checking the number of missing values, dropping missing values, and replacing some values in the dataset.

After cleaning the data, the **categorical variables are converted into numerical variables** using the replace function. The dependent variable is separated from the independent variables, and the data is split into training and testing datasets using the train_test_split function.

Finally, a **support vector machine (SVM) model** is created using the svm.SVC function with a linear kernel. The model is fit to the training dataset, and the accuracy is calculated for both the training and testing datasets using the accuracy_score function from sklearn.metrics.
