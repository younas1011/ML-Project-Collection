# Fake News Prediction Using Logistic Regression
This project uses Logistic Regression to classify news articles as Real (0) or Fake (1).
The dataset contains article text, title, author, and a label that shows whether the news is real or fake.

## What the code does
* Loads the Fake News dataset
* Cleans and preprocesses the text
* Removes stopwords and applies stemming
* Converts text into numerical form using TF-IDF
* Splits the data into training and test sets
* Trains a Logistic Regression model
* Checks accuracy on both training and test data
* Predicts whether new input news is Real or Fake

## Steps in the project
1. Import required libraries
2. Load the dataset
3. Handle missing values
4. Combine author and title into one content field
5. Apply text cleaning and stemming
6. Convert text to numerical features using TF-IDF
7. Separate features and labels
8. Split data into train and test sets
9. Train the Logistic Regression model
10. Evaluate accuracy
11. Test the model with a sample input

## Result
* Accuracy on training data
* Accuracy on test data
* Final prediction for the given news sample

## How to run
* Make sure the dataset file is available
* Install required libraries (e.g, numpy, pandas, nltk, scikit-learn)
* Run the script in your environment
