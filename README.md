# insurance_regression_analysis
# 📊 Insurance Cost Analysis & Regression Models

A comprehensive Machine Learning project in Python covering end-to-end data preprocessing, categorical feature encoding (LabelEncoder), feature scaling (StandardScaler), and model comparisons across multiple regression algorithms using the Insurance Dataset.

---

## 📌 Project Overview

This project aims to predict and classify insurance charges using various machine learning algorithms. The workflow follows these key steps:

1. Data Preprocessing:
   * Encoded categorical features (gender, smoker, region) into numerical values using LabelEncoder.
   * Standardized features using StandardScaler to ensure optimal performance for gradient-based models.
2. Modeling:
   * Implemented both linear and non-linear regression models to predict continuous costs.
   * Transformed the continuous target variable into a binary indicator (above vs. below mean) to evaluate a classification model.
3. Visualization:
   * Plotted separate subplots using Matplotlib to visualize and compare the decision boundaries and fit curves of each algorithm.

---

## 🛠 Technologies & Libraries

* Python 3.x
* Pandas (Data loading and manipulation)
* NumPy (Numerical operations)
* Scikit-Learn (Preprocessing & ML algorithms)
* Matplotlib (Data visualization)

---

## 🤖 Implemented Models

1. Linear Regression: Baseline model capturing the linear relationship between features and insurance charges.
2. Polynomial Regression (Degree 2): Captures non-linear relationships and feature interactions.
3. SGD Regressor: Linear regression fitted using Stochastic Gradient Descent optimization.
4. Logistic Regression: Binary classification evaluating probability distribution (expenses higher/lower than average).

---

## 🚀 How to Run

1. Clone the repository:
   `bash
   git clone [https://github.com/YourUsername/YourRepositoryName.git](https://github.com/YourUsername/YourRepositoryName.git)
   cd YourRepositoryName

2. Install required dependencies:
  pip install pandas numpy matplotlib scikit-learn

3. Ensure Data Placement:
Place the insurance.csv file in the project's root directory.

4. Run the code:
Execute insurance_regression_models.ipynb in Jupyter Notebook or run your script.

Results & Visualizations
​Upon execution, a 2 \times 2 grid plot is generated:

Model    Visualization Description
Model  Visualization Description
Linear Regression  Best-fit straight line
Polynomial Regression  Quadratic curve capturing non-linear trends
SGD Regression  Convergence line optimized via gradient descent
Logistic Regression  Sigmoid (S-curve) probability plot for binary target

Author: Sara
🎓 Machine Learning & Data Science Project
