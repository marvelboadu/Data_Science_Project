# Data_Science_Project
Titanic dataset EDA, statistical analysis, and a Logistic Regression survival prediction model _BCS 404 Data Science project.

# Titanic Survival Prediction — Data Science Project

Exploratory Data Analysis, Statistical Analysis, and Machine Learning on the Titanic dataset, built for **BCS 404: Introduction to Data Science with Python** at Accra Technical University.

## Overview

This project applies a complete data science workflow to the Kaggle Titanic dataset (891 passengers, 12 variables) to explore what factors influenced passenger survival, and to build a Logistic Regression model that predicts survival from passenger characteristics.

## What's in this repo

| File | Description |
|---|---|
| `Titanic_Data_Science_Project.ipynb` | Jupyter Notebook containing the full analysis: data acquisition, cleaning, visualisation, statistics, and machine learning |
| `titanic.csv` | The Titanic dataset used for the analysis |
| `Marvellous_Boadu_with_appendix.docx` / `.pdf` | Full written project report, including the Python code appendix |
| `README.md` | This file |

## Project Workflow

1. **Data Acquisition** — Loaded the dataset with Pandas and inspected its shape, columns, and data types.
2. **Data Cleaning** — Handled missing values in `Age` (median), `Embarked` (mode), and `Cabin` (converted to a `Has_Cabin` flag); checked for and removed duplicates.
3. **Data Visualisation** — Produced 6 visualisations: age histogram, passenger class bar chart, age-by-class boxplot, age vs. fare scatter plot, correlation heatmap, and a pairplot.
4. **Statistical Analysis** — Computed descriptive statistics, frequency distributions, and correlation analysis to identify the strongest predictors of survival.
5. **Machine Learning** — Trained a Logistic Regression classifier (Scikit-Learn) on 8 features to predict survival, evaluated with accuracy, a confusion matrix, and a classification report.

## Key Results

- **Overall survival rate:** 38.38%
- **Strongest predictor of survival:** `Pclass` (passenger class), correlation of -0.34
- **Model accuracy:** 81.01% on held-out test data

## Tools & Libraries

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn

## Dataset Source

[Kaggle: Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)

## Author

Marvellous Anim Kofi Boadu
BCS 404 — Introduction to Data Science with Python
Accra Technical University, 2025/2026 Second Semester
