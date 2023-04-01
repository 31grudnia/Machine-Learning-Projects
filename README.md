# Fake News Prediction using Logistic Regression model

This code is implementing a **binary classification** model to classify news articles as either real or fake based on their content. The dataset used is 'train.csv', which contains news articles along with their labels.

The code begins by importing the necessary libraries, loading the dataset into a pandas DataFrame, and checking for missing values. The missing values are then replaced with an empty string.

The author name and news title are merged into a single column named 'content' using string concatenation.

A **stemming function** is defined to preprocess the text data. This function removes any non-alphabetic characters, converts the text to lowercase, tokenizes the text, removes stopwords, and applies Porter stemming to each word. The stemming function is then applied to the 'content' column using the 'apply' method.

The text data is then converted into numerical data using the **TfidfVectorizer**. This vectorizer calculates the term frequency-inverse document frequency for each word in the text corpus, which is then used to convert the text into a matrix of numbers.

The data is split into training and testing sets using the 'train_test_split' method from sklearn. The model used is **Logistic Regression**, which is trained on the training set. The accuracy score is calculated for both the training and testing sets using the 'accuracy_score' method from sklearn.
