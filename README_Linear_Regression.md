# 🏠 House Price Prediction using Linear Regression

## 📌 Task Objective
To implement and understand simple and multiple linear regression models for predicting housing prices using Scikit-learn, Pandas, and Matplotlib.

## 📊 Dataset
- **Source**: [Kaggle - Housing Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- The dataset includes various features of houses such as area, bedrooms, bathrooms, parking, etc.

## 🛠️ Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📈 Steps Followed

### 1. Data Import and Preprocessing
- Loaded the dataset using Pandas.
- Checked and handled missing values.
- Converted categorical columns using one-hot encoding.

### 2. Feature Selection
- Defined independent features (`X`) and target variable (`y`).

### 3. Data Splitting
- Split data into 80% training and 20% testing using `train_test_split`.

### 4. Model Training
- Trained a `LinearRegression` model using Scikit-learn.

### 5. Model Evaluation
- Evaluated model using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

### 6. Visualization
- Plotted regression line for single-feature prediction.
- Visualized data distribution and correlation heatmaps.

### 7. Coefficient Interpretation
- Printed coefficients to understand feature importance.

## 🔢 Evaluation Metrics

| Metric | Value (Example) |
|--------|------------------|
| MAE    | 122433.45        |
| MSE    | 28912345678.12   |
| R²     | 0.84             |

## 🤔 What I Learned
- How linear regression models work.
- Difference between simple and multiple regression.
- Model evaluation using regression metrics.
- Handling categorical data in regression problems.
