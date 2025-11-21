# 📈 Simple Linear Regression – Age and Systolic Blood Pressure (SBP)

This mini-project is a practice exercise in simple linear regression using Python and scikit-learn.  
The goal is to model the relationship between age and systolic blood pressure (SBP).

---

## 📊 Dataset

- File: data/health_linear_regression.csv  
- Rows: 300  
- Columns:
  - age — age in years  
  - systolic_bp — systolic blood pressure (mmHg)

The dataset is synthetic but designed to resemble real epidemiologic patterns:

- No missing values  
- Positive linear trend between age and systolic BP  
- Useful for practicing:
  - train/test split  
  - simple linear regression  
  - model fitting and visualization  
  - R² performance evaluation  

---

## ⚙️ Methods

### 1. Importing required libraries
- pandas  
- numpy  
- matplotlib  
- scikit-learn (LinearRegression, metrics, model_selection)

### 2. Steps performed

1. Load dataset  
2. Split into training (80%) and testing (20%)  
3. Fit a Simple Linear Regression model  
4. Visualize regression line on training and test sets  
5. Evaluate model using R² score
---

## 📦 Project Structure

simple-linear-regression-blood-pressure/
│
├── data/
│   └── health_linear_regression.csv
│
├── notebooks/
│   └── simple_linear_regression_exercise.ipynb
│
└── README.md
---

## ▶️ Run the Notebook

Open the .ipynb file using:

- Jupyter Notebook
- JupyterLab
- VS Code (Python + Jupyter extensions)

Install scikit-learn if needed:

pip install scikit-learn
---

## 📉 Results

### R² Score (Test Set)

R² = 0.71
This means 71% of the variance in systolic blood pressure is explained by age,  
which is reasonable for a single-feature regression model.

### Visualization

- Training set: scatter plot + regression line  
- Testing set: scatter plot + regression line  
(Shows inside the notebook)

---

## 🎯 Conclusion

This project demonstrates:

- How simple linear regression works  
- How to interpret regression plots  
- How to evaluate a regression model using R²  
- A clean workflow for ML exercises  

This repository is part of my learning path in machine learning for epidemiology and public health.

[health_linear_regression.csv](https://github.com/user-attachments/files/23683080/health_linear_regression.csv)
[simple_linear_regression_exercise.ipynb](https://github.com/user-attachments/files/23683089/simple_linear_regression_exercise.ipynb)
