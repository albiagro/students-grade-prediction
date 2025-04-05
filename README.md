# 📊 Student Performance Prediction – Portuguese Course

This project focuses on **data analysis** and **grade prediction** for students enrolled in a Portuguese language course. Using the **Student Alcohol Consumption** dataset, we aim to understand how **personal, social, and academic features** influence students' final grades.

---

## 🧠 Objectives

- Analyze the dataset to identify correlations between student characteristics and academic performance.
- Build predictive models to estimate the **final grade (G3)**.
- Explore the impact of **alcohol consumption** and other factors such as **school attendance**, **family background**, and **leisure time**.

---

## 🗂️ Dataset

**Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/student+performance)

**File used:** `student-por.csv`

### Key Features:

- **Personal**: gender, age, address, parental job.
- **Social**: family relationships, free time, going out with friends.
- **Academic**: number of absences, weekly study time, extra educational support.
- **Alcohol consumption**: during the week (`Dalc`) and on weekends (`Walc`).
- **Grades**: G1 (first period), G2 (second period), G3 (final grade).

---

## 🔍 Data Analysis

- Descriptive statistics and data exploration.
- Correlation analysis via **heatmaps**.
- Feature impact analysis on the final grade.
- Pattern recognition related to student performance.

---

## 🤖 Predictive Models

The following machine learning algorithms were tested:

- **Linear Regression**
- **Random Forest**
- **Gradient Boosting**
- **Support Vector Regression (SVR)**

### Evaluation Metrics:

- RMSE (Root Mean Squared Error)
- R² Score
- Actual vs. predicted grade comparison

---

## 📈 Key Insights

- Previous grades (G1 and G2) are the strongest predictors of final grade (G3).
- Higher alcohol consumption is **moderately** associated with lower performance.
- Other relevant factors include weekly study time and school support programs.

---

## 🛠️ Requirements

- Python ≥ 3.8
- Libraries:
  - `pandas`
  - `numpy`
  - `seaborn`
  - `matplotlib`
  - `scikit-learn`
