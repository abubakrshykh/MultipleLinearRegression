# MultipleLinearRegression
# Hiring Salary Prediction Model
This code builds a machine learning model to predict the salary of a potential employee based on their years of experience, level of education, and interview score. The model is trained on a dataset of past hiring information, and uses linear regression to make its predictions.

# Libraries Used

NumPy: A library for working with arrays and numerical operations.

Pandas: A library for data manipulation and analysis, used to load and preprocess the dataset.

Matplotlib: A library for creating visualizations, used to plot the data.

scikit-learn: A machine learning library with tools for data preprocessing, model selection, and evaluation.

word2number: A library for converting English words to numeric values, used to preprocess the data.

# Working of overall model
1- The dataset is loaded into a Pandas DataFrame, with features like years of experience, level of education, and interview score, as well as the corresponding salary values.

2- The data is preprocessed by using the word2number library to convert English words to numeric values, and by replacing any NaN values with 0.

3- The data is split into training and testing sets using the train_test_split function from scikit-learn.

4- A linear regression model is instantiated using the LinearRegression class from scikit-learn.

5- The model is trained on the training data using the fit method, which fits a linear equation to the data that minimizes the sum of squared errors.

6- The model is used to predict the salary values for the testing data using the predict method.

7- The ***Accuracy*** of the model is evaluated using the R² score, which is a statistical measure that represents how well the model fits the data. The R² score ranges from 0 to 1, with higher values indicating a better fit.

In summary, the model uses linear regression to find a linear equation that relates the input features to the output salary values. This equation is then used to predict the salary of new potential employees based on their years of experience, level of education, and interview score.
