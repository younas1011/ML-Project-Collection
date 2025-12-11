# Parkinson’s Disease Prediction Using Support Vector Machine (SVM)
This project uses a Support Vector Machine (SVM) classifier to predict whether a person has Parkinson’s disease based on various vocal and biomedical features. The dataset contains 24 attributes per patient, and the target column (status) indicates the presence (1) or absence (0) of Parkinson’s disease.

## What the code does
* Loads the Parkinson’s dataset
* Shows the first and last rows of the dataset
* Checks dataset size and info
* Checks missing values
* Displays statistical summary of the data
* Analyzes distribution of the target variable (status)
* Groups data based on Parkinson's vs Healthy
* Separates features and target columns
* Splits the data into training and testing sets
* Standardizes the data using StandardScaler
* Trains an SVM model with a linear kernel
* Calculates accuracy on both training and test data
* Builds a predictive system for diagnosing new input data

## Steps in the project
1. Import required libraries
2. Load the dataset
3. View first 5 rows
4. View last 5 rows
5. Check dataset size
6. Check dataset info
7. Check missing values
8. Show statistical summary
9. Analyze target distribution
10. Group dataset based on status
11. Separate features and target
12. Split data into train and test sets
13. Apply data standardization
14. Train the SVM model
15. Evaluate accuracy
16. Build predictive system for new input data

## Result
* Accuracy score on training data
* Accuracy score on test data
* Predictive system output showing whether a person has Parkinson’s disease or not

## How to run
* Make sure the dataset file (parkinsons.csv) is available
* Install required libraries (numpy, pandas, scikit-learn)
* Run the script in Python / Jupyter Notebook / Google Colab
