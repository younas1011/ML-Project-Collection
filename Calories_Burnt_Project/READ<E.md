# Calories Burnt Prediction Using XGBoost Regressor
This project uses the XGBoost Regressor to predict the number of calories burnt during exercise based on various physical and activity-related features. The dataset contains exercise details of users, and the target column represents the calories burnt.

## What the code does
* Loads the calories and exercise datasets
* Displays the first few rows of both datasets
* Combines the two datasets into a single DataFrame
* Checks dataset shape and information
* Checks for missing values
* Displays statistical summary of the data
* Visualizes data distributions using plots
* Analyzes correlation between features using a heatmap
* Encodes categorical column (Gender) into numerical values
* Separates features and target variable
* Splits the data into training and testing sets
* Trains an XGBoost Regressor model
* Predicts calories burnt on test data
* Evaluates the model using Mean Absolute Error

## Steps in the project
1. Import required libraries
2. Load calories dataset
3. Load exercise dataset
4. Combine both datasets
5. Check dataset shape
6. Check dataset information
7. Check missing values
8. Show statistical summary
9. Visualize gender distribution
10. Visualize feature distributions
11. Analyze feature correlation
12. Encode categorical data
13. Separate features and target
14. Split data into train and test sets
15. Train XGBoost Regressor model
16. Make predictions on test data
17. Evaluate model performance

## Result
* Predicted calories burnt values
* Mean Absolute Error (MAE) of the model
* Model accurately predicts calories burnt based on exercise data

## How to run
* Make sure the dataset files are available
* Install required libraries (numpy, pandas, matplotlib, seaborn, scikit-learn, xgboost)
* Run the script in Python / Jupyter Notebook / Google Colab
