# Heart-Failure-Prediction

This project focuses on predicting the presence of heart disease in patients using various machine learning models. The dataset used is based on cardiovascular health indicators such as cholesterol level, resting blood pressure, and chest pain type.

## 📁 Dataset
Source: Kaggle - Heart Failure Prediction Dataset

Features include:

Age, Sex, ChestPainType, RestingBP, Cholesterol, FastingBS, RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope

Target: HeartDisease (0 = No, 1 = Yes)

## 📊 Exploratory Data Analysis
Detected and handled zero values in Cholesterol and RestingBP.

Performed outlier analysis using boxplots and pairplots.

Visualized feature relationships using Seaborn heatmap and pairplot.

## ⚙️ Preprocessing
Handled missing and zero values.

Encoded categorical variables using one-hot encoding.

Split dataset into train/test sets (80/20).

Applied feature scaling where required.

## 🧠 Models Trained
# Model	Accuracy (%)
Logistic Regression -	88.59

Random Forest -	88.04

SVC -	85.87

XGBoost -	84.78 

## 📈 Evaluation Metrics
Accuracy, Precision, Recall, F1-score

Confusion Matrix

Classification Report

## 🧪 Libraries Used
pandas, numpy, matplotlib, seaborn, sklearn, xgboost

## 🏁 How to Run
1. Install the required libraries using:
pip install -r requirements.txt

2. Run test.ipynb notebook in Jupyter or VS Code.
