# Uncertainty-Aware Credit Risk Prediction

## Overview
The goal is to develop an uncertainty-aware machine learning system for credit risk assessment using calibrated probabilistic models and selective prediction.

The system uses:
- Probabilistic classification
- Post-hoc calibration
- Reliability analysis
- Selective prediction
- Cost-sensitive decision modeling

to improve reliability in important financial decisions.

## Dataset
German Credit Dataset (UCI Repository)

- 1000 samples
- Mixed categorical and numerical features
- Binary credit risk classification

## Methods

### Preprocessing
- One-hot encoding for categorical features
- Standardization for numerical features
- Stratified train-test split

### Modeling
- Logistic Regression baseline
- Class-weighted training for imbalance

### Calibration
- Platt scaling (sigmoid)
- Isotonic regression
- Reliability diagrams
- Brier score
- Expected Calibration Error (ECE)

### Uncertainty Estimation
- Probability-based confidence scoring
- Selective prediction via reject option
- Risk–coverage analysis

### Decision Modeling
- Cost-sensitive evaluation
- Abstention vs prediction trade-offs
- Financial risk simulation


## Future Work
- Bayesian neural networks
- Conformal prediction
- Deep ensembles
- Fairness-aware uncertainty analysis