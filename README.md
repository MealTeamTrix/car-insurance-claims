# Car Insurance Logistic Regression Analysis

This project performs a univariate logistic regression analysis on each feature in a car insurance dataset to determine which single feature is the best predictor of the outcome.

## Files

- `car_insurance_analysis.ipynb`: Jupyter notebook with the full analysis.
- `car_insurance.csv`: CSV file containing the dataset (not included here).
- `requirements.txt`: Python dependencies for the project.

## How It Works

1. Loads and cleans the dataset (`credit_score` and `annual_mileage` are imputed with their mean).
2. Fits a logistic regression model (`outcome ~ feature`) for each feature.
3. Calculates the accuracy of each model using the confusion matrix.
4. Identifies the feature with the highest accuracy.

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
