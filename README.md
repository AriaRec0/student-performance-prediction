# Student Performance Prediction Using Machine Learning

A machine learning project predicting students' final exam grades (G3) using demographic, academic, and social features from the UCI Student Performance Dataset.

## 📊 Project Overview

This project develops and compares three regression algorithms:
- Linear Regression (baseline)
- Random Forest Regressor
- Gradient Boosting Regressor (best performance:  R² = 0.85, RMSE = 1.89)

## 🎯 Key Features

- **Feature Engineering**: Created `avg_prev_grade` and `total_absences`
- **Exploratory Data Analysis**: Correlation analysis and distribution visualizations
- **Model Comparison**:  Comprehensive evaluation using R², RMSE, and MAE metrics
- **Feature Importance**: Identified G1 and G2 as dominant predictors (75% accuracy)

## 📁 Dataset

- **Source**: [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/student+performance)
- **Students**: 395 (Mathematics course)
- **Features**: 33 (demographic, social, academic)
- **Target**: G3 (final grade, 0-20 scale)

## 🛠️ Technologies Used

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## 📈 Model Performance

| Model | Train R² | Test R² | RMSE | MAE |
|-------|----------|---------|------|-----|
| Linear Regression | 0.82 | 0.78 | 2.15 | 1.65 |
| Random Forest | 0.96 | 0.82 | 1.95 | 1.52 |
| **Gradient Boosting** | **0.93** | **0.85** | **1.89** | **1.45** |

## 📊 Top 5 Features

1. G2 (Second period grade) - 45.2%
2. G1 (First period grade) - 29.8%
3. avg_prev_grade - 8.7%
4. failures - 4.2%
5. absences - 3.1%

## 🚀 Getting Started

### Installation

```bash

# Install dependencies
pip install -r requirements.txt
