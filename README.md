# Breast Cancer Wisconsin (Diagnostic) Dataset Analysis

This notebook analyzes the Breast Cancer Wisconsin (Diagnostic) Dataset from Kaggle to build a Logistic Regression model for predicting breast cancer diagnosis.

## Dataset

The dataset contains features computed from digitized images of fine needle aspirate (FNA) of a breast mass. It includes 569 observations and 32 features. The target variable is 'diagnosis', which indicates whether the mass is malignant (M) or benign (B).

## Analysis Steps

The notebook follows these steps:

1.  **Import Libraries**: Imports necessary libraries like pandas and seaborn.
2.  **Download Dataset**: Downloads the dataset from Kaggle using the Kaggle API.
3.  **Load & Explore Data**: Loads the data into a pandas DataFrame and performs initial exploration, including checking for null values and examining the distribution of the target variable.
4.  **Data Cleaning**: Removes the 'Unnamed: 32' column which contains only null values.
5.  **Label Encoding**: Encodes the 'diagnosis' column from categorical (M/B) to numerical (1/0).
6.  **Split Dataset & Feature Scaling**: Splits the data into training and testing sets and scales the features using StandardScaler.
7.  **Build a Logistic Regression Model**: Builds a Logistic Regression classifier and trains it on the training data.
8.  **Performance Evaluation**: Evaluates the model's performance using a confusion matrix and accuracy score.

## Results

The Logistic Regression model achieved an accuracy of [Insert Accuracy Score Here] on the test set. The confusion matrix shows [Interpret Confusion Matrix Here, e.g., number of true positives, true negatives, false positives, false negatives].

## How to Run

1.  Ensure you have a Kaggle account and have set up your Kaggle API credentials.
2.  Run the cells in the notebook sequentially.

## Dependencies

-   pandas
-   seaborn
-   sklearn
-   kaggle
