# Customer Churn Prediction

Predict which customers of a fictional California telecom company are likely to leave. This is a learning project focused on classification, data cleaning, model evaluation, and explaining results.

## Dataset

Use IBM's Telco Customer Churn CSV:
https://github.com/IBM/watsonx-ai-samples/blob/master/cpd4.5/data/customer_churn/WA_FnUseC_TelcoCustomerChurn.csv

Download the CSV and place it in this folder. The dataset contains 7,043 fictional customer records. The target is whether a customer churned.

## Project question

Given information known about a customer, can a model identify customers at greater risk of leaving? The goal is to compare the model with a simple baseline and explain when its predictions are useful or wrong.

## Build order

1. Load the CSV with pandas. Print its shape, column names, first rows, missing-value counts, and churn counts.
2. Decide which column is the target and which columns are usable inputs. Exclude customer identifiers and any information that reveals churn after it happened.
3. Explore churn rates across a few useful customer groups. Make clear charts with matplotlib.
4. Split the data into training, validation, and test sets. Keep the churn proportion similar in each set.
5. Train a simple baseline classifier. Record its results.
6. Prepare numeric and categorical inputs in a scikit-learn Pipeline. Train logistic regression.
7. Compare models using a confusion matrix, precision, and recall. Explain what false positives and false negatives mean here.
8. Inspect incorrect predictions and choose a decision threshold based on a simple business scenario, such as contacting a limited number of customers.
9. Evaluate the chosen approach once on the untouched test set.
10. Clean up the code and update this README with results, limitations, and instructions to run it.

## Tools

Python, pandas, scikit-learn, matplotlib. NumPy is optional.

## Notes

This is a fictional sample dataset, so model performance does not prove that the same approach will work at a real company. Avoid using columns that contain the answer or information only available after the customer left.

## How to run

To be completed after the first working version.
