# Titanic Survival Prediction Using Logistic Regression
This project uses Logistic Regression to predict whether a passenger survived the Titanic disaster based on various personal and travel-related features. The dataset contains passenger information, and the target column (Survived) indicates survival (1) or not survived (0).

## What the code does
* Loads the Titanic dataset
* Shows the first few rows of the dataset
* Checks dataset size and information
* Checks missing values in each column
* Handles missing values in Age and Embarked columns
* Drops the Cabin column due to excessive missing values
* Displays statistical summary of the dataset
* Analyzes distribution of the target variable (Survived)
* Visualizes survival distribution using count plots
* Visualizes survival based on gender and passenger class
* Encodes categorical columns (Sex and Embarked) into numerical values
* Separates features and target variable
* Splits the data into training and testing sets
* Trains a Logistic Regression model
* Calculates accuracy on both training and test data

## Steps in the project
1. Import required libraries
2. Load the dataset
3. View first 5 rows
4. Check dataset shape
5. Check dataset information
6. Check missing values
7. Handle missing values
8. Drop unnecessary columns
9. Show statistical summary
10. Analyze target distribution
11. Visualize data using seaborn plots
12. Encode categorical columns
13. Separate features and target
14. Split data into train and test sets
15. Train Logistic Regression model
16. Evaluate accuracy on training data
17.  Evaluate accuracy on test data

## Result
* Accuracy score on training data
* Accuracy score on test data
* Model predicts whether a passenger survived or not

## How to run
* Make sure the dataset file (train.csv) is available
* Install required libraries (numpy, pandas, matplotlib, seaborn, scikit-learn)
* Run the script in Python / Jupyter Notebook / Google Colab
