# Travel Insurance Prediction using Naive Bayes

This project illustrates the use of Naive Bayes classifiers to predict whether a customer will purchase travel insurance based on demographic and employment-related data.

## Overview

The dataset `travel-insurance.csv` includes customer information such as age, employment type, and travel history. The goal is to build and evaluate Naive Bayes models to predict the likelihood of buying travel insurance.

## Objectives

1. Load and clean the dataset, perform exploratory data analysis and visualization.
2. Preprocess the data and split it into training and test sets.
3. Train a **Gaussian Naive Bayes (GaussianNB)** model and tune the `var_smoothing` parameter using cross-validation.
4. Train a **Mixed Naive Bayes (MixedNB)** model.
5. Evaluate and compare both models using precision, recall, and F1-score metrics.

## Discussion

The analysis includes:

* Identifying features that most influence the purchase decision.
* Assessing the independence assumption of Naive Bayes.
* Observing data trends and patterns during exploration.
* Examining the effect of hyperparameter tuning on model performance.
* Suggesting additional data that could improve model accuracy.

## Tools and Libraries

* Python
* pandas, numpy
* scikit-learn
* mixed-naive-bayes
* matplotlib, seaborn

## File Structure

```
├── travel-insurance.csv
├── 240141-assignment1-notebook.ipynb
├── README.md
└── requirements.txt
```

## Results

Both GaussianNB and MixedNB were trained and tested. While GaussianNB performed consistently, MixedNB demonstrated stronger handling of datasets containing both numerical and categorical features.

This project was developed as part of a machine learning assignment on Naive Bayes classification.
