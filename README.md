# 🏠 House Price Prediction using Machine Learning

This project predicts house sale prices using **Machine Learning** and **Linear Regression**. The project covers the complete basic machine learning workflow, including data loading, data preprocessing, categorical encoding, train-test splitting, feature scaling, model training, and model evaluation.

## 📌 Project Overview

The model uses housing-related features such as:

* MSSubClass
* MSZoning
* LotArea
* LotConfig
* BldgType
* OverallCond
* YearBuilt
* YearRemodAdd
* Exterior1st
* BsmtFinSF2
* TotalBsmtSF

The target variable is **SalePrice**.

The dataset contains **2,919 records and 13 original columns**. After preprocessing and categorical encoding, the model uses **33 input features**.

## 🚀 Features

* Load house price dataset using Pandas
* Explore dataset structure and statistics
* Handle missing values
* Remove unnecessary `Id` column
* Encode categorical variables using One-Hot Encoding
* Split data into training and testing sets
* Apply feature scaling using StandardScaler
* Train a Linear Regression model
* Predict house prices
* Evaluate model performance using:

  * R² Score
  * Mean Absolute Error (MAE)
  * Root Mean Squared Error (RMSE)
  * Mean Absolute Percentage Error (MAPE)

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Jupyter Notebook**

## 🤖 Machine Learning Model

The project uses:

**Linear Regression**

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)
```

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Categorical Encoding
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Linear Regression
   ↓
Prediction
   ↓
Model Evaluation
```

## 📊 Model Evaluation

The current Linear Regression model produced the following results on the test set:

| Metric   |    Result |
| -------- | --------: |
| R² Score |    0.3741 |
| MAE      | 30,829.94 |
| RMSE     | 41,138.56 |
| MAPE     |    0.1874 |

These results represent the current baseline implementation in the notebook.

## 📂 Project Structure

```text
House-Price-Prediction/
│
├── house_price_predictor.ipynb
├── HousePricePrediction.csv
└── README.md
```

