Analysis of Red Wine Quality Using Physicochemical Properties
This project explores the relationship between physicochemical properties and sensory evaluations of Portuguese Vinho Verde red wine using regression modeling techniques. It includes data preprocessing, exploratory analysis, and model building to identify significant predictors of wine quality.

Project Files
Red_Wine_Analysis_Report.pdf: Detailed project report outlining the analysis process, results, and insights derived from the dataset.
winequality-red-filtered.csv: Processed dataset with shortened column names for efficient modeling and analysis.
winequality-red-raw.csv: Original dataset with full descriptive column names sourced from the UCI Machine Learning Repository.
Red_Wine_Analysis.Rmd: R Markdown file containing all code and visualizations used for data preprocessing, analysis, and regression modeling.

Key Features
Dataset: Includes 1,599 observations of physicochemical properties and sensory ratings of red wine (quality scored from 0 to 10).
Exploratory Data Analysis: Scatterplots, histograms, and correlation matrices to understand variable relationships.

Modeling:
Applied regression models (OLS, LAD, Huber).
Addressed multicollinearity by removing highly correlated variables.
Validated assumptions with statistical tests (Shapiro-Wilk, Breusch-Pagan).
Findings: Significant predictors include alcohol (+0.347), volatile acidity (-0.787), and chlorides (-2.119).