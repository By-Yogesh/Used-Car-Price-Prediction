# 🚗 Used Car Price Prediction

A Machine Learning project that predicts the selling price of used cars using different regression algorithms and data analysis techniques.

---

## 📌 Project Overview

This project focuses on predicting used car prices based on various factors such as:

- Brand
- Fuel Type
- Transmission
- Mileage
- Engine Capacity
- Power
- Car Age
- Kilometers Driven
- Owner Type
- Location

The project includes:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Outlier Handling
- Model Training
- Model Evaluation

---

## 🎯 Problem Statement

Used car prices vary due to multiple factors, making manual price estimation difficult.

The goal of this project is to build a Machine Learning model that can accurately predict used car prices using historical car data.

---

## 📂 Dataset Information

- Dataset Size: **7,253 Rows × 13 Columns**
- Dataset Type: Structured CSV Dataset
- Target Variable: `Price`

### Important Features
- Year
- Kilometers_Driven
- Fuel_Type
- Transmission
- Owner_Type
- Mileage
- Engine
- Power
- Seats
- Location

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

Performed:
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis

### Key Insights
- Most cars are Manual transmission.
- Diesel and Petrol cars dominate the dataset.
- Power and Engine size strongly affect car price.
- Mileage has a negative correlation with price.

---

## 🧹 Data Preprocessing

### Steps Performed
- Removed unnecessary columns
- Fixed data types
- Handled missing values
- Outlier detection using IQR
- Feature Engineering
- One Hot Encoding
- Feature Scaling using StandardScaler

---

## 📈 Outlier Handling

Outliers were detected using:
- Boxplots
- IQR Method

### IQR Formula
```python
IQR = Q3 - Q1
```

---

## ⚙️ Feature Engineering

Created a new feature:

```python
Car_Age = 2024 - Year
```

Dropped:
- Name
- Year

---

## 🤖 Machine Learning Models Used

- Linear Regression
- Random Forest Regressor
- KNN Regressor
- SVR (Support Vector Regressor)
- Stacking Regressor

---

## 📉 Model Performance

| Model | R2 Score | MAE (₹) |
|------|------|------|
| SVR | 0.75 | 214,440 |
| Stacking Regressor | 0.77 | 224,656 |
| Random Forest | 0.75 | 240,694 |
| Linear Regression | 0.76 | 249,489 |
| KNN | 0.64 | 307,047 |

---

## 🏆 Best Performing Model

### Stacking Regressor
- Best overall prediction performance
- Highest R2 Score
- Low prediction error

---

## 📷 Visualizations Included

- Histograms
- KDE Plots
- Boxplots
- Scatter Plots
- Heatmaps
- Pairplots
- Violin Plots

---

## ▶️ How to Run the Project

### Clone Repository
```bash
git clone <your-repo-link>
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run Notebook / Script
```bash
jupyter notebook
```

---

## 📌 Future Improvements

- Hyperparameter Tuning
- Deployment using Streamlit or Flask
- Real-time car price prediction web app
- Deep Learning models

---

## 👨‍💻 Author

### Yogesh

- Data Science & Machine Learning Enthusiast
- Exploring AI, NLP, and LLMs
- Building real-world ML projects

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub.

