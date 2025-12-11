# Big Mart Sales Prediction Using XGBoost Regressor
This project uses the XGBoost Regressor to predict sales of retail products based on multiple item and outlet features. The dataset contains both numerical and categorical attributes, and the target column represents the total sales for each product-outlet pair.

## What the code does
* Loads the Big Mart dataset
* Shows first and last rows of the dataset
* Checks dataset size and info
* Identifies categorical features
* Checks for missing values
* Handles missing values using mean and mode
* Displays statistical summary of numerical features
* Visualizes distributions of key numeric and categorical columns
* Cleans inconsistent categorical values
* Encodes categorical columns using Label Encoding
* Splits the dataset into features and target
* Splits data into training and testing sets
* Trains an XGBoost Regressor model
* Calculates R² accuracy on training and test data
* Builds a predictive system to estimate product sales

## Steps in the project
1. Import required libraries
2. Load the dataset
3. View first 5 rows
4. View last 5 rows
5. Check dataset size
6. Check dataset info
7. Identify categorical columns
8. Check for missing values
9. Handle missing values (mean & mode)
10. Show statistical summary
11. Analyze distributions of:
12. Item Weight
13. Item Visibility
14. Item MRP
15. Item Outlet Sales
16. Outlet Establishment Year
17. Analyze categorical column distributions:
18. Item Fat Content
19. Item Type
20. Outlet Size
21. Clean inconsistent category labels
22. Encode categorical columns
23. Split features and target
24. Split data into train and test sets
25. Train XGBoost Regressor
26. Evaluate model accuracy
27. Build predictive system for new inputs

## Result
* R² score on training data
* R² score on test data
* Predictive system output showing estimated sales for new inputs

## How to run
* Make sure the dataset file (Train.csv) is available
* Install required libraries (numpy, pandas, seaborn, matplotlib, scikit-learn, xgboost)
* Run the script in Python / Jupyter Notebook / Google Colab
