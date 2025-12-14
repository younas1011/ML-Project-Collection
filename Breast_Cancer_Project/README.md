# Breast Cancer Prediction Using Logistic Regression
This project uses Logistic Regression to predict whether a breast tumor is Malignant (0) or Benign (1) based on medical features extracted from breast cancer diagnostic data. The dataset is loaded directly from the sklearn library and contains numerical features describing cell nuclei characteristics.

## What the code does
* Loads the Breast Cancer dataset from sklearn
* Displays dataset details and structure
* Converts the dataset into a pandas DataFrame
* Adds the target label column
* Checks dataset shape and information
* Checks for missing values
* Displays statistical summary of the data
* Analyzes the distribution of the target variable
* Separates features and target labels
* Splits the data into training and testing sets
* Trains a Logistic Regression model
* Calculates accuracy on training and test data
* Builds a predictive system for new input data

## Steps in the project
1. Import required libraries
2. Load the breast cancer dataset from sklearn
3. Print the dataset details
4. Convert dataset into a pandas DataFrame
5. Display first 5 rows of the dataset
6. Add target label column to the DataFrame
7. Display last 5 rows of the dataset
8. Check number of rows and columns
9. Get dataset information
10. Check for missing values
11. Display statistical summary
12. Check target variable distribution
13. Analyze feature values grouped by target label
14. Separate features and target variable
15. Split data into training and testing sets
16. Train Logistic Regression model
17. Evaluate accuracy on training data
18. Evaluate accuracy on test data
19. Build a predictive system for new input

## Result
* Accuracy score on training data
* Accuracy score on test data
* Final prediction showing whether the breast cancer is Malignant or Benign

## How to run
* Open the notebook in Google Colab or Jupyter Notebook
* Make sure required libraries are installed (numpy, pandas, scikit-learn)
* Run all cells sequentially
* Provide input values to test the predictive system
