# Diabetes Prediction using Decision Tree and Random Forest

## Project Overview

This project predicts whether a person has diabetes using machine learning classification algorithms.

The project uses:

* Decision Tree Classifier
* Random Forest Classifier

The dataset used is `diabetes.csv`, where the target variable is `Outcome`.

* `0` → No Diabetes
* `1` → Diabetes

The project also includes:

* Decision Tree visualization
* Diabetes outcome count visualization
* Accuracy comparison of models

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

---

## Dataset Information

The dataset contains medical features used to predict diabetes.

### Features

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age

### Target Variable

`Outcome`

* `0` = No Diabetes
* `1` = Diabetes

---

## Machine Learning Workflow

1. Load dataset using Pandas
2. Split features (`X`) and target (`y`)
3. Split training and testing data
4. Train a Decision Tree model
5. Visualize the Decision Tree
6. Train a Random Forest model
7. Evaluate accuracy of both models
8. Visualize diabetes count

---

## Algorithms Used

### 1. Decision Tree Classifier

A Decision Tree is a supervised machine learning algorithm used for classification and prediction. It works by splitting data into branches based on feature values.

Used in this project to:

* Train classification model
* Visualize decision-making process

### 2. Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

Used in this project to:

* Improve prediction performance
* Compare accuracy with Decision Tree

---
## Output

The program will:

* Train Decision Tree model
* Display Decision Tree visualization
* Train Random Forest model
* Print model accuracies
* Display diabetes count graph
---

## Visualization

### Decision Tree Visualization

Shows how the Decision Tree makes predictions based on dataset features.

### Diabetes Count Visualization

Displays the count of diabetic and non-diabetic patients using a bar chart.

---
## Author

R.Hemanth Babu
