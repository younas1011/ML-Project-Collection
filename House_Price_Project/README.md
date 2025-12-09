# House Price Prediction Using XGBoost
This project uses the XGBoost Regressor to predict house prices based on different housing-related features.
The dataset contains various numerical attributes for each house, and the target column represents the final price value.

##What the code does
* Loads the Boston House Price dataset
* Shows basic information about the data
* Splits the data into training and testing sets
* Trains an XGBoost Regressor model
* Checks accuracy on both training and test data
* Predicts the price for new input values

## Steps in the project
1. Import required libraries
2. Load the dataset
3. Convert data to a DataFrame
4. Add the target (price) column
5. Check for missing values
6. Explore data statistics
7. Analyze feature correlation
8. Split data into train and test sets
9. Train the model
10. Evaluate accuracy
11. Test the model with sample input

## Result
* The model prints:
* Accuracy score (R²) on training data
* Accuracy score (R²) on test data
* Final predicted price for the given input

## How to run
* Make sure the dataset is available in your environment
* Run the script in your Python or Colab environment
