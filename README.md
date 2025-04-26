# Iris Classification Project

## Problem Statement

The goal of this project is to classify iris flowers into one of three species — Setosa, Versicolor, or Virginica — based on four key features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The model should achieve high classification accuracy and generalize well to unseen data using proper machine learning practices.

## Dataset Description

- The Iris dataset consists of 150 records.
- Features:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
- Label:
  - Species (Setosa, Versicolor, Virginica)

The Iris dataset is a classic benchmark dataset available in the UCI Machine Learning Repository and scikit-learn datasets.

## Technologies Used

- Python 3.x
- Pandas – Data manipulation
- NumPy – Numerical computations
- Seaborn / Matplotlib – Data visualization
- Scikit-Learn – Machine Learning models
- Jupyter Notebook / VS Code – Development environment

## Project Workflow

### 1. Understanding the Problem
- Classify flowers into the correct species based on 4 features.

### 2. Data Preparation
- Loaded the dataset from CSV.
- Checked for missing values.
- Dropped duplicates and handled outliers using the IQR method.
- Standardized or normalized features when needed.

### 3. Exploratory Data Analysis (EDA)
- Created countplots, scatterplots, pairplots, boxplots, histograms, and distplots.
- Analyzed correlation between features.
- Visualized species distributions.

### 4. Feature Engineering
- Removed outliers using the IQR method.
- Ensured dataset was clean and balanced across all classes.

### 5. Model Selection and Training
- Trained multiple classifiers:
  - Perceptron Classifier
  - Logistic Regression
- Trained models using 80 percent of the data and tested on 20 percent.

### 6. Model Evaluation
- Evaluated models using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)
- Visualized decision boundaries and confusion matrices.

### 7. Hyperparameter Tuning
- GridSearchCV or Cross-validation suggested (optional).

### 8. Model Interpretation and Insights
- Identified the most important features (Petal Length, Petal Width).
- Visualized decision regions for better model understanding.

## Results

| Metric                  | Perceptron Model | Logistic Regression |
|--------------------------|------------------|----------------------|
| Accuracy                 | [Insert Accuracy] | [Insert Accuracy]     |
| Best features identified | Petal measurements | Petal measurements  |

Both models achieved high performance, with Logistic Regression generally performing slightly better.

## Key Insights

- Petal length and petal width are the most influential features for classification.
- Setosa is linearly separable from the other classes.
- Versicolor and Virginica are harder to distinguish.



