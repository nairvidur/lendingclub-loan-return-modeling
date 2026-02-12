📊 LendingClub Loan Return Modeling

Quantitative Credit Return Forecasting using Regularized Regression

Overview

This project develops a quantitative framework to forecast realized loan returns using over 1 million LendingClub loans (2008–2017).

The objective is to model cross-sectional return variation across consumer credit instruments using financial and borrower characteristics, with strict out-of-sample validation.

Dataset

Source: LendingClub historical loan data

Observations: 1M+ loans

Features: Interest rate, loan amount, FICO score, income, debt ratios, loan status, etc.

Target Variable: Realized loan return

Note: Raw dataset excluded from repository due to size constraints.

Methodology
1. Exploratory Data Analysis

Distributional analysis of returns and borrower characteristics

Correlation matrix for feature dependence

Return dispersion across risk buckets

2. Data Preprocessing

Missing value treatment

Feature scaling (standardization)

One-hot encoding of categorical variables

Interaction terms and nonlinear features

3. Modeling Framework

Implemented and compared:

Linear Regression

Ridge Regression

Lasso Regression

Elastic Net

Hyperparameters tuned using validation set performance.

Evaluation

Performance measured using:

In-sample R²

Out-of-sample R²

Kaggle leaderboard R²

Final leaderboard R²: 0.04876
Top-15 ranking.