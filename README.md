# 🏗️ House Price Predictor: Regression Modeling Workflow with Python

## 📌 Short Description
A machine learning project that applies regression techniques to predict house prices using real-world tabular data. This end-to-end workflow demonstrates core skills in data preprocessing, exploratory data analysis, feature selection, model building, evaluation, and comparison using Python’s data science ecosystem.

---

## 📊 Project Overview

This project highlights fundamental machine learning competencies by walking through a complete regression pipeline using Python. It includes data exploration, cleaning, feature engineering, model implementation, and performance evaluation.

---

## 🚀 Key Highlights

### 📂 Data Loading & Exploration
- Load data from an Excel file.
- Use `.info()` and `.describe()` to understand data structure and summary statistics.
- Identify missing values using `.isnull().sum()`.

### 🧹 Data Cleaning
- Drop irrelevant columns using `.drop()` based on initial inspection.

### 🛠️ Feature Engineering & Selection
- Generate a correlation heatmap to identify relationships between variables.
- Select features based on a defined correlation threshold with the target variable.

### 🧠 Model Building
Implemented and trained two regression models using **scikit-learn**:
- ✅ Decision Tree Regressor
- ✅ Polynomial Linear Regression (via pipeline)

### 📈 Model Evaluation
- Evaluate model performance using **Mean Absolute Percentage Error (MAPE)**.
- Visualize predicted vs. actual values using line plots for model interpretability.

### 📊 Model Comparison
- Compare the performance of different models using bar plots of evaluation metrics.

### 🖼️ Visualizations
- Correlation Heatmap
- Actual vs Predicted Value Plots
- Model Comparison Bar Chart

---

## 🧰 Tech Stack & Libraries

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`

---
