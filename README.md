# Celebal Technologies Data Science Internship — Weekly Assignments (2026)

This repository contains my weekly assignment submissions completed as part of the Celebal Technologies Data Science Internship Program.

## Assignment Progress

| Week | Topic | Status |
|------|-------|--------|
| Week 1 | Python, NumPy, Linear Algebra, Statistics, Probability & ML Foundations | Completed |
| Week 2 | Tesla Deliveries Forecasting and Time Series Analysis | Completed |
| Week 3 | Customer Intelligence System using K-Means & DBSCAN Clustering | Completed |

## Topics Covered in Week 1

* NumPy Arrays and Matrix Operations
* Vector Norms and Linear Algebra
* Eigenvalues and Eigenvectors
* Singular Value Decomposition (SVD)
* Statistical Analysis and Hypothesis Testing
* Probability Distributions
* Bayes' Theorem and Naive Bayes
* Population Stability Index (PSI)
* Central Limit Theorem (CLT)
* Data Visualization using Matplotlib

## Tools Used

* Python
* NumPy
* Pandas
* SciPy
* Matplotlib
* Google Colab

## Key Learnings



Through this assignment, I gained practical experience with NumPy operations, matrix transformations, eigenvalues and eigenvectors, probability distributions, Bayes' theorem, and the Central Limit Theorem. I also learned how data visualization helps interpret mathematical and statistical concepts.

## Assignment Highlights

- Implemented linear algebra concepts using NumPy

- Visualized statistical distributions using Matplotlib

- Applied Bayes' theorem for spam classification

- Explored Population Stability Index (PSI) for data drift detection

- Demonstrated the Central Limit Theorem through simulation


# Week 2 – Tesla Deliveries Forecasting and Time Series Analysis

## Overview

This assignment focuses on exploratory data analysis, feature engineering, machine learning, and basic time series analysis using Tesla delivery and production data from 2015–2025.

## Objectives

* Analyze Tesla production and delivery trends.
* Perform data cleaning and preprocessing.
* Create meaningful visualizations for business insights.
* Engineer features for forecasting.
* Build and evaluate machine learning models.
* Compare Linear Regression and Random Forest performance.
* Conduct a stationarity test using the Augmented Dickey-Fuller (ADF) test.

### Assignment Highlights

* Performed Exploratory Data Analysis (EDA) on Tesla production and delivery data from 2015–2025.
* Analyzed delivery trends across different vehicle models and regions.
* Investigated relationships between production units and estimated deliveries using correlation analysis.
* Created lag and rolling mean features to capture historical delivery patterns.
* Built and evaluated a Linear Regression model for delivery forecasting.
* Applied 5-Fold Cross Validation to assess model stability and generalization.
* Tuned a Random Forest Regressor using GridSearchCV.
* Compared model performance using MAE, RMSE, and R² Score.
* Identified the most influential features through feature importance analysis.
* Conducted an Augmented Dickey-Fuller (ADF) test to evaluate time-series stationarity.
* Generated forecasts and compared predicted values against actual deliveries.

## Dataset

**Tesla Deliveries and Production Dataset (2015–2025)**

The dataset contains information related to Tesla vehicle production, deliveries, models, regions, and other factors that influence demand and supply patterns over time.

## Tasks Performed

* Dataset inspection and quality checks
* Missing value and duplicate analysis
* Exploratory Data Analysis (EDA)
* Correlation analysis
* Feature engineering (Label Encoding, Lag Features, Rolling Mean)
* Linear Regression model training
* Cross-validation
* Random Forest with GridSearchCV
* Feature importance analysis
* ADF stationarity testing
* Forecast generation and model comparison

## Key Learnings

* Understanding time-series oriented train-test splitting
* Importance of feature engineering in forecasting
* Model evaluation using MAE, RMSE, and R² Score
* Comparing linear and ensemble machine learning models
* Interpreting stationarity in time series data

## Files Included

* `week2_ArpitaDas.ipynb` – Week 2 assignment notebook
* `tesla_deliveries_dataset_2015_2025.csv` – Dataset used for analysis

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels
* Jupyter Notebook


# Week 3 – Customer Intelligence System using Clustering

## Overview

This assignment focuses on unsupervised learning techniques to build a Customer Intelligence / Country Segmentation system using socio-economic and health indicators.

The objective is to identify meaningful country groups, compare clustering approaches, and derive actionable insights from the discovered segments.

## Objectives

- Clean and preprocess country-level socio-economic data.
- Standardize features for clustering.
- Determine the optimal number of clusters using the Elbow Method.
- Build and evaluate a K-Means clustering model.
- Compare results with DBSCAN.
- Visualize clusters using PCA.
- Interpret socio-economic patterns across clusters.

### Assignment Highlights

- Performed data cleaning, missing value handling, and duplicate removal.
- Applied StandardScaler for feature normalization.
- Used the Elbow Method to determine the optimal number of clusters.
- Built a K-Means clustering model with three clusters.
- Evaluated clustering performance using the Silhouette Score.
- Implemented DBSCAN for comparative clustering analysis.
- Reduced data dimensions using PCA for visualization.
- Identified economically developed, developing, and high-risk country groups through cluster interpretation.

## Dataset

**Country Socio-Economic & Health Indicators Dataset**

The dataset contains country-level indicators such as income, health expenditure, child mortality, exports, imports, inflation, life expectancy, and other socio-economic metrics used for clustering and segmentation.

## Tasks Performed

- Dataset inspection and preprocessing
- Missing value imputation
- Duplicate record removal
- Feature scaling using StandardScaler
- Elbow Method analysis
- K-Means clustering
- Silhouette Score evaluation
- DBSCAN clustering
- PCA-based visualization
- Cluster interpretation and socio-economic insights

## Key Learnings

- Understanding the workflow of unsupervised learning.
- Selecting the optimal number of clusters using the Elbow Method.
- Evaluating clustering quality with the Silhouette Score.
- Comparing centroid-based and density-based clustering algorithms.
- Applying PCA for dimensionality reduction and visualization.
- Interpreting clusters to derive meaningful socio-economic insights.

## Files Included

- `week3_ArpitaDas.ipynb` – Week 3 assignment notebook
- `country_data.csv` – Dataset used for clustering and segmentation

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Author

Arpita Das

B.Tech Computer Science & Engineering
