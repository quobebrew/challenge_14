# challenge_14
# Machine Learning Trading Bot Project Summary

## Overview
This project focuses on enhancing an existing algorithmic trading system for a financial advisory firm. The goal is to improve the system's performance by incorporating machine learning algorithms that can adapt to new data. The project involves establishing a baseline performance, tuning the trading algorithm, evaluating a new machine learning classifier, and creating an evaluation report.

## Steps

### 1. Establish Baseline Performance
- Import OHLCV dataset into a Pandas DataFrame.
- Generate trading signals using SMA values.
- Split the data into training and testing datasets.
- Use the `SVC` classifier model to fit the training data and make predictions.
- Review classification report and create predictions DataFrame.
- Create a cumulative return plot as baseline performance.

### 2. Tune Baseline Trading Algorithm
- Tune the training algorithm by adjusting the size of the training dataset.
- Tune the trading algorithm by adjusting SMA input features.
- Choose the set of parameters that best improves the trading algorithm returns.

### 3. Evaluate a New Machine Learning Classifier
- Import a new classifier (e.g., AdaBoost, DecisionTreeClassifier, LogisticRegression).
- Fit another model with the new classifier using the original training data.
- Backtest the new model to evaluate its performance.

