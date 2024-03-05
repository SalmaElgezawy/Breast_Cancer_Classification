## Breast Cancer Classification Machine Learning Project

## Overview
This project focuses on the classification of breast cancer tumors using the Logistic Regression algorithm. The dataset includes various features extracted from breast cancer biopsies. The following sections outline the steps involved in the project, from data exploration to model building and evaluation.

## Exploratory Data Analysis (EDA)
The initial phase of the project involves exploring and understanding the dataset. Key EDA steps include:

* Loading the dataset ('data.csv').
* Inspecting the structure of the dataset.
* Displaying the first 5 rows of the DataFrame to get an overview of the data.
* Showing statistical measures and checking for null values.
* Exploring the distribution of the target column "diagnosis" through histograms.
* Visualizing the count of benign vs. malignant cases.

## Data Preprocessing
Data preprocessing steps are crucial for preparing the data for machine learning. In this project:

- Unneeded columns, including 'Unnamed: 32' and 'id', are dropped for feature extraction.
- The dataset is split into training and testing sets using 'train_test_split'.
- Features are scaled using 'StandardScaler' to converge the training and testing data and ensure all features are on the same scale.

## Building Logistic Regression Model
The machine learning model used for breast cancer classification is Logistic Regression. The Logistic Regression model is trained on the preprocessed data, and its performance is evaluated using accuracy, cross-validation, a classification report, and a confusion matrix.

## Model Parameters:
- Tolerance ('tol'): 0.0001
- Regularization strength ('C'): 2
- Maximum number of iterations ('max_iter'): 1000
- Random state: 42

## Results and Evaluation
The accuracy of the Logistic Regression model on the training set is found to be approximately 97.4%. Additional evaluation metrics include:

- Cross-validation accuracy.
- Classification report providing precision, recall, and F1-score.
- Confusion matrix visualizing the model's predictions.

## Code Structure
The code is organized into sections, covering data exploration, preprocessing, and model building. Each section is commented to provide clarity and understanding.

## Dependencies
Ensure you have the required Python libraries installed: 'pip install -r requirements.txt'

## Requirements

Ensure you have the following dependencies installed:
- Python (>= 3.6)
- NumPy
- pandas
- scikit-learn
- matplotlib
- seaborn
