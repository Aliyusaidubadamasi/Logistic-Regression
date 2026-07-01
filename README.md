# Logistic Regression - Airline Customer Satisfaction Prediction

## Project Overview
This project analyzes airline passenger survey data using Logistic Regression to predict customer satisfaction and identify key drivers of passenger experience.

## Dataset Description
- **Source**: Airline passenger satisfaction survey
- **Rows**: 129,880 passengers
- **Features**: 25 features including service ratings, flight details, and passenger demographics
- **Target**: satisfaction (satisfied/dissatisfied)

## Key Findings
- **Model Accuracy**: 84.5%
- **ROC-AUC**: 0.928
- **Best Predictors**: Inflight wifi service, Ease of Online booking, Seat comfort
- **Strongest Negative Driver**: Total Delay

## Setup Instructions

### Prerequisites
- Python 3.7+
- Jupyter Notebook or Google Colab

### Install Required Libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
