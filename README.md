# Credit risk modelling using Logistic Regression

## Problem Statement

Predict the loan defaulters using a Logistic Regression model on the credit risk data and calculate credit scores

(Logistic regression is a popular statistical technique used for binary classification problems, such as credit risk assessment. It models the relationship between the input features and the probability of default, allowing for risk prediction)

## Objectives

* perform data exploration, preprocessing and visualization
* implement Logistic Regression using manual code or using sklearn library
* evaluate the model using appropriate performance metrics
* develop a credit scoring system

## Dataset

The dataset chosen for this project is the '**Give Me Some Credit**' dataset which can be used to build models for predicting loan repayment defaulters. This dataset contains 150000 data points and 11 features.
(*Dataset is uploaded in the repository and can be downloaded from there.)

## Project Setup
Follow the steps below to set up the project:

1. Clone the project repository or download the project files to your local machine.

2. Open it in Jupyter Notebook or Google Colab.

3. Download the dataset.

## Usage
1. Open the ipynb file.

2. Load the credit risk dataset into the notebook using the appropriate file reading function (e.g., pd.read_csv() in the case of a CSV file).

3. Preprocess the dataset by performing data cleaning, handling missing values, encoding categorical variables, and splitting the data into training and testing sets.

4. Implement the logistic regression model using scikit-learn's LogisticRegression module. Set the appropriate hyperparameters and regularization techniques based on the dataset and problem requirements.

5. Train the logistic regression model using the training data and evaluate its performance using suitable evaluation metrics (e.g., accuracy, precision, recall).

6. Make predictions on the test data using the trained model and assess the accuracy of the predictions.

7. Visualize the results, such as confusion matrix, to gain insights and interpret the model's performance.

## Troubleshooting
* Ensure that the dataset file is correctly specified and placed in the same directory as the ipynb Notebook file.

* Check for any missing libraries or dependencies and install them using the pip install command if necessary.
