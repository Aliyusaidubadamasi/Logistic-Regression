# Logistic Regression - Airline Customer Satisfaction Prediction

## Project Overview
This project analyzes airline passenger survey data using Logistic Regression to predict customer satisfaction and identify key drivers of passenger experience.

## Dataset
- **Source**: Airline passenger satisfaction survey
- **Rows**: 129,880 passengers
- **Features**: 22 features including service ratings, flight details, and demographics
- **Target**: satisfaction (satisfied/dissatisfied)

## Results Summary
| Metric | Score |
|--------|-------|
| Accuracy | 84.5% |
| Precision | 88.0% |
| Recall | 82.0% |
| F1-Score | 84.9% |
| ROC-AUC | 0.928 |

## Top Drivers of Satisfaction
1. Inflight wifi service
2. Ease of Online booking
3. Seat comfort
4. Inflight entertainment
5. Online support

## Top Drivers of Dissatisfaction
1. Total Delay
2. Class (Economy)
3. Age

## Business Recommendations
1. Upgrade Inflight Wi-Fi
2. Simplify Online Booking
3. Improve Seat Comfort
4. Reduce Delays

## Setup
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
