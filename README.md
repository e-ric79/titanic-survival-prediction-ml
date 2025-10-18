# Titanic Survival Prediction - ML Model

## Overview
Machine learning model to predict Titanic passenger survival using Logistic Regression.

## Results
- **Accuracy: 81%** - Correctly predicted survival for 145 out of 179 test passengers
- Dataset: 891 passengers, 6 features

## Key Features
- Pclass (Passenger Class)
- Sex (Gender)
- Age
- Fare (Ticket Price)
- SibSp (Siblings/Spouses)
- Parch (Parents/Children)

## What Drives Survival?
- **Female passengers:** 98.6% survival chance (females prioritized)
- **1st class passengers:** Higher survival rate (better lifeboat access)
- **Higher fare:** Better survival (richer = better cabins)
- **Younger passengers:** Better survival rates

## Prediction Examples

**Young Female, 1st Class, $500 ticket:**
- Model Prediction: **98.6% survival** ✓

**Old Male, 3rd Class, $50 ticket:**
- Model Prediction: **5.3% survival** ✗

## Tools
- Python, scikit-learn, pandas, Logistic Regression
- Train/Test Split (80/20)


---

*First ML Classification Project - Demonstrates supervised learning workflow*
