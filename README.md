# Data Science & Analytics Internship Projects

## Overview

This repository contains three Data Science and Machine Learning projects completed as part of a Data Science & Analytics Internship. The projects demonstrate essential data science skills including data exploration, visualization, preprocessing, machine learning model development, and model evaluation.

The repository covers:

1. Iris Dataset Exploration and Visualization
2. Insurance Claim Prediction using Linear Regression
3. Personal Loan Acceptance Prediction using Logistic Regression

---

# Technologies and Libraries Used

The following tools and libraries were used across all projects:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

# Project 1: Iris Dataset Exploration and Visualization

## Objective

The objective of this project was to understand how to load, inspect, summarize, and visualize a dataset using Python. Various visualizations were created to identify patterns and relationships among flower measurements in the Iris dataset.

## Dataset Information

**Dataset:** Iris Dataset

**Source:** Loaded using `seaborn.load_dataset("iris")`

**Dataset Shape:** 150 rows × 5 columns

### Features

* sepal_length
* sepal_width
* petal_length
* petal_width
* species

### Missing Values

No missing values were found in the dataset.

## Workflow

* Loaded dataset using Pandas and Seaborn
* Inspected dataset structure and summary information
* Checked for missing values
* Created visualizations:

  * Scatter Plot
  * Histogram
  * Box Plot

## Key Insights

* Petal length and sepal length show a strong positive relationship.
* Setosa is clearly separated from the other species.
* Sepal length follows an approximately bell-shaped distribution.
* Sepal width contains a few potential outliers.

---

# Project 2: Insurance Claim Prediction using Linear Regression

## Objective

The goal of this project was to predict medical insurance charges using a Linear Regression model and identify factors that significantly influence insurance costs.

## Dataset Information

**Dataset:** Medical Cost Personal Dataset

### Features

* age
* sex
* bmi
* children
* smoker
* region

### Target Variable

* charges

## Workflow

### Data Preparation

* Loaded dataset using Pandas
* Explored dataset structure
* Checked for missing values
* Removed duplicates
* Applied One-Hot Encoding to categorical features

### Exploratory Data Analysis

Visualizations included:

* Age vs Charges Scatter Plot
* BMI vs Charges Scatter Plot
* Smoking Status Box Plot
* Correlation Heatmap

### Model Development

* Linear Regression
* Train-Test Split:

  * 80% Training Data
  * 20% Testing Data

### Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

## Key Insights

* Smoking status has the strongest impact on insurance charges.
* Smokers incur significantly higher medical costs.
* Insurance charges generally increase with age.
* Higher BMI is associated with higher medical expenses.

---

# Project 3: Personal Loan Acceptance Prediction

## Objective

The purpose of this project was to predict whether customers would accept a personal loan offer using classification techniques and customer demographic information.

## Dataset Information

**Dataset:** Bank Marketing Dataset (`bank.csv`)

### Features

The dataset includes information such as:

* Age
* Job
* Marital Status
* Education
* Balance
* Housing Loan
* Personal Loan
* Contact Type
* Campaign Information
* Previous Marketing Outcome

### Target Variable

**deposit**

* Yes → Customer accepted the offer
* No → Customer did not accept the offer

## Workflow

### Data Exploration

* Dataset inspection
* Data type analysis
* Shape and column analysis
* Missing value checking

### Data Preprocessing

* Label Encoding of categorical variables
* Feature scaling using StandardScaler

### Exploratory Data Analysis

Visualizations included:

* Age Distribution Histogram
* Marital Status Count Plot
* Job Category Count Plot

### Model Development

* Logistic Regression
* Train-Test Split:

  * 80% Training Data
  * 20% Testing Data

### Model Evaluation

Performance metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report

  * Precision
  * Recall
  * F1-Score

## Key Insights

* Customer age influences loan acceptance behavior.
* Marital status affects response patterns.
* Job categories contribute to customer decision-making.
* Logistic Regression effectively classified customer responses.
* Feature scaling improved model performance.

---

# Repository Structure

```text
Data-Science-Internship-Projects
│
├── Task1_Iris_Visualization
│   ├── task1_iris.ipynb
│   └── README.md
│
├── Task2_Insurance_Claim_Prediction
│   ├── insurance_claim_prediction.ipynb
│   └── README.md
│
├── Task3_Loan_Acceptance_Prediction
│   ├── bank_marketing_prediction.ipynb
│   └── README.md
│
└── Main README.md
```

---

# How to Run the Projects

## Clone the Repository

```bash
git clone <repository-link>
```

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the desired notebook and run all cells.

---

# Learning Outcomes

Through these projects, the following concepts were practiced:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Linear Regression
* Logistic Regression
* Model Evaluation
* Predictive Analytics

---

# Conclusion

These projects collectively demonstrate a complete data science workflow, from data exploration and visualization to machine learning model development and evaluation. The work highlights the practical application of statistical analysis and predictive modeling techniques using real-world datasets.

---

# Author

**Amina Umer Dar**
Data Science & Analytics Intern
