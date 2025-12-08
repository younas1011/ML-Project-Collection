# Sonar Mine vs Rock Classification

This project uses Logistic Regression to classify sonar signals as either Mine or Rock. The dataset contains 60 numerical values for each signal, and the last column shows the correct label.

## What the code does
* Loads the sonar dataset
* Shows basic information about the data
* Splits the data into training and testing sets
* Trains a Logistic Regression model
* Checks accuracy on both training and test data
* Predicts whether a new input belongs to a Mine or a Rock

## Steps in the project
1. Import required libraries
2. Read the dataset
3. Separate features and labels
4. Split data into train and test sets
5. Train the model
6. Evaluate accuracy
7. Test the model with a sample input

## Result
The model prints:
* Accuracy on training data
* Accuracy on test data
* Final prediction for the given input

## How to run
* Make sure the dataset file is available
* Install required libraries
--- pip install numpy pandas scikit-learn
* Run the script in your environment
