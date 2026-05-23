# 📈 Sales Prediction & Data Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

A machine learning project designed to analyze and predict **Sales** performance based on advertising budgets spent across different channels (TV, Radio, and Newspaper) using Linear Regression.

---

## 🎯 Aim & Objectives
- Perform comprehensive **Data Cleaning** and **Exploratory Data Analysis (EDA)**.
- Analyze correlation trends between sales revenue and advertising channels.
- Build a robust **Linear Regression** model to predict sales and evaluate its performance.

## 📊 Dataset Used
- **Dataset:** Advertising Dataset
- **Source:** Loaded dynamically via online repository URL.
- **Features:**
  - `TV`: Advertising budget spent on TV.
  - `Radio`: Advertising budget spent on Radio.
  - `Newspaper`: Advertising budget spent on Newspaper.
  - `Sales`: Target variable representing sales units sold.

## 🛠️ Tech Stack & Libraries
- **Core:** Python
- **Data Wrangling:** `pandas`, `numpy`
- **Visualization:** `seaborn`, `matplotlib`
- **Predictive Modeling:** `scikit-learn` (`LinearRegression`, `train_test_split`, `mean_absolute_error`, `mean_squared_error`, `r2_score`)

---

## 🚀 How to Setup & Run

### 1. Clone the Repository
```bash
git clone https://github.com/JINAY2910/synent-task5-salesanalysis-jinayshah.git
cd synent-task5-salesanalysis-jinayshah
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the Notebook
```bash
jupyter notebook synent-task5-salesanalysis-jinayshah.ipynb
```
Run the cells sequentially to see the regression lines, residual plots, correlation heatmap, and predictive analytics.

---

## 📈 Methodology & Insights
1. **Correlation Insights:** Discovered that TV advertising budget has the strongest positive correlation with sales, followed by Radio, while Newspaper has a weaker correlation.
2. **Model Training:** Built a Multiple Linear Regression model mapping `[TV, Radio, Newspaper]` to `Sales`.
3. **Performance Metrics:** Evaluated the model using:
   - **R² Score (Coefficient of Determination)** to measure variance explained.
   - **MAE** & **MSE** to measure average absolute error and standard error variance.

---
*Developed by Jinay Shah*
