# Spam Mail Prediction Using Logistic Regression
This project uses Logistic Regression to classify emails as Spam or Ham based on the content of the message. The dataset contains email text messages, and the target column indicates whether the mail is spam (0) or ham (1).

## What the code does
* Loads the email dataset
* Handles missing values
* Encodes spam and ham labels into numerical form
* Separates message text and target labels
* Splits the data into training and testing sets
* Converts text data into numerical feature vectors using TF-IDF
* Trains a Logistic Regression model
* Evaluates accuracy on training and test data
* Builds a predictive system to classify new email messages

## Steps in the project
1. Import required libraries
2. Load the mail dataset
3. Replace missing values
4. View dataset structure and size
5. Encode target labels (spam and ham)
6. Separate messages and labels
7. Split data into training and test sets
8. Convert text data into TF-IDF feature vectors
9. Train Logistic Regression model
10. Evaluate accuracy on training data
11. Evaluate accuracy on test data
12. Build a predictive system for new emails

## Result
* Accuracy score on training data
* Accuracy score on test data
* Predictive system output showing whether the mail is Spam or Ham

## How to run
* Make sure the dataset file (mail_data.csv) is available
* Install required libraries (numpy, pandas, scikit-learn)
* Run the script in Python / Jupyter Notebook / Google Colab
