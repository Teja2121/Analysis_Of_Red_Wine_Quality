# Analysis of Red Wine Quality Using Physicochemical Properties

This project explores the relationship between physicochemical properties and sensory evaluations of Portuguese Vinho Verde red wine. Using regression modeling techniques, the study identifies significant predictors of wine quality and provides actionable insights.

---

## Table of Contents
- [Introduction](#introduction)
- [Project Files](#project-files)
- [Key Features](#key-features)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling and Findings](#modeling-and-findings)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)

---

## Introduction

The analysis focuses on Portuguese Vinho Verde red wine, investigating how physicochemical properties influence sensory evaluations. By leveraging regression modeling, the project provides a better understanding of the factors contributing to wine quality, scored on a scale of 0 to 10.

---

## Project Files

- **Red_Wine_Analysis_Report.pdf**: Comprehensive report detailing the analysis process, results, and insights derived from the dataset.
- **winequality-red-filtered.csv**: Processed dataset with shortened column names for efficient modeling and analysis.
- **winequality-red-raw.csv**: Original dataset with full descriptive column names sourced from the UCI Machine Learning Repository.
- **Red_Wine_Analysis.Rmd**: R Markdown file containing all code and visualizations for data preprocessing, analysis, and regression modeling.

---

## Key Features

### Dataset:
- **Observations**: 1,599 samples of red wine.
- **Attributes**: Physicochemical properties (e.g., acidity, chlorides, alcohol) and sensory quality ratings (score from 0 to 10).

### Exploratory Data Analysis:
- Scatterplots, histograms, and correlation matrices to explore relationships between variables.

### Modeling:
- **Regression Techniques**:
  - Ordinary Least Squares (OLS)
  - Least Absolute Deviations (LAD)
  - Huber Regression
- **Multicollinearity**:
  - Addressed by removing highly correlated variables.
- **Validation**:
  - Statistical tests, including Shapiro-Wilk and Breusch-Pagan.

### Findings:
- Significant predictors of wine quality:
  - **Alcohol**: Positive impact (+0.347).
  - **Volatile Acidity**: Negative impact (-0.787).
  - **Chlorides**: Negative impact (-2.119).

---

## Technologies Used

- **R Programming**: For data preprocessing, exploratory analysis, and modeling.
- **R Markdown**: For creating reproducible reports.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Teja2121/Analysis_Of_Red_Wine_Quality
   ```
2. Open the `Red_Wine_Analysis.Rmd` file in RStudio.
3. Load the dataset (`winequality-red-raw.csv` or `winequality-red-filtered.csv`).
4. Run the R Markdown file to replicate the analysis and visualize the findings.

---

Feel free to contribute or raise issues to enhance this project!
