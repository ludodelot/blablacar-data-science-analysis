# BlaBlaCar Data Science Analysis

Data Science project focused on data cleaning, exploratory analysis, visualization, feature-based business insights, and Premium Club subscription prediction using a BlaBlaCar-style dataset.

## Project Overview

This notebook was developed as part of the **Data Science for Business (IS525E)** course.

The project covers four main stages:

1. **Data import and manipulation**
2. **Data cleaning and preprocessing**
3. **Data visualization and business analysis**
4. **Binary classification model to predict Premium Club subscription**

The objective is to extract useful insights from driver and trip data, and to build a simple machine learning model that predicts whether a user is likely to subscribe to the Premium Club.

---

## Main Contents

### 1. Data Import & Manipulation
- Load the dataset from Excel
- Inspect structure and summary statistics
- Normalize missing values
- Remove columns with excessive missing data
- Drop rows with very low missing-value proportions
- Impute numerical values by `driver_status`
- Impute categorical variables using mode
- Perform grouped queries and custom driver-level exploration

### 2. Data Visualization & Analysis
- Average pricing by satisfaction level
- Maximum evaluations by driver status
- Driver age distribution
- Lyon departure analysis
- Business Index calculation
- Comfort Index calculation

### 3. Machine Learning
- Define a binary classification target
- Prepare features and target variable
- Train/test split
- Logistic Regression model
- Basic evaluation:
  - Accuracy
  - Confusion Matrix
  - Classification Report

---

## Files

- `20260402_BlaBlaCar_DataScience_LDELOT.ipynb` → main notebook with the full analysis

---

## Tech Stack

- Python
- pandas
- matplotlib
- scikit-learn
- Jupyter Notebook

---

## Project Structure

```bash
blablacar-data-science-analysis/
│
├── 20260402_BlaBlaCar_DataScience_LDELOT.ipynb
├── README.md
└── data/
    └── BlaBla-Car_Data.xlsx   
