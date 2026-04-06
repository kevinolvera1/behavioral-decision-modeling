# Executive Function, Stress, and Impulsive Decision-Making

## Overview
This project analyzes whether executive function (EF) buffers the relationship between perceived stress and impulsive decision-making using behavioral data from the Human Connectome Project (HCP-YA 2025).

Impulsivity is operationalized using delay discounting (AUC), where lower values indicate greater impulsivity.

## Research Question
Does executive function moderate the relationship between perceived stress and impulsive decision-making?

## Methods
- Data cleaning and validation
- Z-score standardization of variables
- Executive function composite construction
- OLS moderation modeling with HC3 robust standard errors
- Nonlinear model comparison
- Predictive modeling using OLS, Ridge, and Elastic Net
- Train/test split and cross-validation

## Key Findings
- The relationship between stress and impulsivity was weak
- No meaningful stress × executive function interaction was observed
- Predictive performance was near zero out of sample
- Results suggest impulsive decision-making may depend on broader or more complex factors

## Interpretation
This analysis illustrates a full behavioral data workflow, from hypothesis-driven modeling to evaluation of out-of-sample generalization. It also highlights the distinction between relationships that are statistically detectable and those that meaningfully predict behavior.

## Tools Used
- Python (pandas, numpy, matplotlib)
- statsmodels (regression, robust inference)
- scikit-learn (Ridge, Elastic Net, model evaluation)

## Author
Kevin Olvera
