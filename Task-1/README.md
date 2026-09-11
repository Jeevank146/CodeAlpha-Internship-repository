# 🌸 Iris Flower Classification

## CodeAlpha Data Science Internship - Task 1

This project focuses on classifying Iris flowers into three different species using machine learning.

The classification is based on four flower measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The three target classes are:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

## 🎯 Objective

The main objective of this project is to build and evaluate machine learning classification models that can predict the species of an Iris flower based on its measurements.

## 📊 Dataset

The dataset was obtained from Kaggle and contains:

- **150 samples**
- **4 numerical features**
- **3 target classes**
- **No missing values**
- **50 samples per species**

### Features

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal |
| Sepal Width | Width of the sepal |
| Petal Length | Length of the petal |
| Petal Width | Width of the petal |

## 🔬 Project Workflow

1. Data Loading
2. Data Inspection
3. Missing Value Analysis
4. Exploratory Data Analysis
5. Data Visualization
6. Feature and Target Separation
7. Label Encoding
8. Train-Test Split
9. Feature Scaling
10. Machine Learning Model Training
11. Model Comparison
12. KNN Hyperparameter Tuning
13. Model Evaluation
14. New Flower Prediction

## 🤖 Machine Learning Models

The following classification algorithms were evaluated:

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest

## 📈 Results

The models were compared using the same training and testing data with feature scaling.

The best-performing model was:

**Support Vector Machine (SVM)**

**Test Accuracy: 96.67%**

## 🔍 Prediction Example

A new Iris flower with the following measurements was tested:

```text
Sepal Length = 5.1
Sepal Width  = 3.5
Petal Length = 1.4
Petal Width  = 0.2
