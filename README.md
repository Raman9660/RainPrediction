# 🌧 Rain Prediction Using Logistic Regression

This project aims to predict whether it will rain tomorrow using weather data and logistic regression. It includes EDA, visualization, data preprocessing, model training, and evaluation.

## 📁 Files in this Repository

- rain_prediction_using_logistic_regression.ipynb – Main notebook with code, EDA, model training, and plots
- weatherAUS.csv – Dataset containing historical weather data (from [Kaggle](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package))

---

## 📌 Problem Statement

The goal is to predict the target variable RainTomorrow (Yes/No) based on various features like temperature, humidity, wind speed, and more using *logistic regression*.

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for null values and cleaned the dataset
- Plotted distribution of rainfall across locations
- Analyzed correlations between variables
- Used Seaborn and Plotly for attractive and interactive visualizations

---

## 🧪 Model

- *Algorithm Used*: Logistic Regression
- *Libraries*: pandas, numpy, matplotlib, seaborn, plotly, sklearn
- Performed train-test split
- Evaluated accuracy, precision, recall, and confusion matrix

---

## 📈 Results

- Trained logistic regression model on processed dataset
- Achieved reasonable accuracy on test data
- Visualized prediction performance using confusion matrix and plots

---

## 🛠 Requirements

Make sure to install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
