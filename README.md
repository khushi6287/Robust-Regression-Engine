# 🏠 Robust Regression Engine for House Price Prediction

## 📌 Project Overview

This project aims to develop a robust machine learning regression system for predicting house prices using multiple regression algorithms. The project compares traditional linear models with advanced machine learning techniques while applying regularization and cross-validation to improve prediction accuracy and reduce overfitting.

The project was implemented in **Google Colab** using **Python** and **Scikit-learn**.

---

# 🎯 Objectives

- Predict house prices using machine learning.
- Implement Regularization techniques.
- Apply different Cross Validation methods.
- Build Tree-Based Regression models.
- Develop Support Vector Regression models.
- Compare model performance using evaluation metrics.
- Select the best-performing regression model.

---

# 📂 Dataset

**Dataset Name:**

Advanced_Regression_HousePrice_Dataset_3800.xlsx

**Target Variable:**

house_price_inr

**Input Features include:**

- Property ID
- Sale Date
- Area (sqft)
- Bedrooms
- Bathrooms
- Location Score
- Property Age
- Distance from City
- Near School
- Near Metro
- Crime Rate Index

---

# 🛠 Technologies Used

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# 📚 Machine Learning Models Implemented

## 1. Ridge Regression
- L2 Regularization
- Hyperparameter Tuning using GridSearchCV

## 2. Lasso Regression
- L1 Regularization
- Feature Selection
- Hyperparameter Tuning

## 3. Decision Tree Regressor

- Decision Tree Model
- Hyperparameter Optimization

## 4. Random Forest Regressor

- Ensemble Learning
- Feature Importance Analysis

## 5. Support Vector Regression (SVR)

- Linear Kernel
- RBF Kernel
- Hyperparameter Tuning

---

# 🔄 Cross Validation Techniques

The following validation techniques were implemented:

- K-Fold Cross Validation
- Stratified K-Fold Cross Validation
- Leave-One-Out Cross Validation (LOOCV)
- Time Series Split

---

# 📊 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 📈 Data Preprocessing

The dataset was prepared using the following preprocessing steps:

- Handling Missing Values
- Duplicate Value Check
- Feature Engineering
- Date Conversion
- Feature Scaling using StandardScaler
- Train-Test Split (80:20)

---

# 📊 Visualizations

The project includes the following visualizations:

- Correlation Heatmap
- House Price Distribution
- Area vs House Price Scatter Plot
- Ridge vs Lasso Coefficient Comparison
- Feature Importance Plot
- Actual vs Predicted Plot
- Residual Plot
- Model Comparison Graph
- Cross Validation Comparison

---

# 📁 Project Structure

```
Robust_Regression_Engine/
│
├── Advanced_Regression_HousePrice_Dataset_3800.xlsx
├── Robust_Regression_Engine.ipynb
├── README.md
└── Images/
    ├── Heatmap.png
    ├── FeatureImportance.png
    ├── ModelComparison.png
    └── ResidualPlot.png
```

---

# 🚀 How to Run

1. Open Google Colab.
2. Upload the notebook.
3. Upload the dataset file.
4. Install the required libraries if necessary.
5. Run all notebook cells sequentially.
6. Review the generated evaluation metrics and visualizations.

---

# 📋 Results

The project compares the performance of multiple regression models based on:

- Prediction Accuracy
- R² Score
- RMSE
- MAE

The best-performing model is selected based on the highest R² Score and the lowest prediction error.

---
# 🎓 Learning Outcomes

Through this project, the following concepts were explored:

- Regularization Techniques
- Model Selection
- Hyperparameter Tuning
- Cross Validation
- Ensemble Learning
- Feature Engineering
- Model Evaluation
- Regression Analysis


# 📜 License

This project was developed for educational and academic purposes.
