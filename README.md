# Flower Classification

## Project Overview

This project is a Machine Learning classification project using the Iris dataset. The goal is to classify flowers into three species based on their sepal and petal measurements.

The project uses Logistic Regression and Decision Tree classifiers and compares their accuracy.

## Dataset

The Iris dataset is loaded using Scikit-learn's built-in `load_iris()` dataset.

It contains four features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The target classes are:

* Setosa
* Versicolor
* Virginica

## Project Steps

### 1. Load Iris Dataset

The Iris dataset is loaded using Scikit-learn.

### 2. Exploratory Data Analysis (EDA)

The dataset is explored using:

* First and last rows
* Dataset shape
* Dataset information
* Duplicate values
* Missing values
* Statistical summary
* Species distribution

### 3. Feature Pair Visualization

Seaborn's pairplot is used to visualize relationships between the Iris features and compare the three species.

### 4. Machine Learning Models

Two classification models are trained:

* Logistic Regression
* Decision Tree Classifier

### 5. Accuracy Comparison

The accuracy of both models is calculated and compared.

### 6. Confusion Matrix

A confusion matrix is plotted for the Logistic Regression model to visualize correct predictions and possible misclassifications.

### 7. Misclassification Interpretation

The off-diagonal values of the confusion matrix are checked to identify any misclassified flowers.

### 8. New Flower Prediction

The project includes a simple command-line interface where the user enters:

* Sepal length
* Sepal width
* Petal length
* Petal width

The trained Logistic Regression model then predicts the flower species.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Seaborn
* Matplotlib

## Project Structure

```text
Syntecxhub_Flower_Classification/
│
├── main.py
└── README.md
```

## Results

Both Logistic Regression and Decision Tree achieved an accuracy of **1.0 (100%)** on the test set used in this project.

The confusion matrix showed no misclassifications for the test data.

## How to Run

1. Clone the repository.
2. Open the project in PyCharm or another Python IDE.
3. Install the required libraries.
4. Run `main.py`.
5. Enter the flower measurements when prompted.

## Author

Eman Fatima

