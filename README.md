# AI_Assignment_1_Customer_Churn
Artificial Intelligence assignment implementing customer churn prediction using machine learning classification models.
# Customer Churn Prediction Using Machine Learning

## Overview

This project was developed as part of the Artificial Intelligence course at the University of Lahore.

The objective of the project is to build a machine learning system that predicts whether a telecom customer is likely to churn or remain with the company.

## Dataset

The project uses the Telco Customer Churn dataset containing customer information such as:

* Customer demographics
* Tenure
* Internet service
* Contract type
* Payment method
* Monthly charges
* Total charges
* Churn status

The target variable is `Churn`.

## Machine Learning Workflow

The project follows these steps:

1. Data loading and understanding
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Feature engineering and categorical encoding
5. Training and testing
6. Model evaluation
7. Model comparison
8. Customer churn prediction

## Models Used

Two classification algorithms were trained and evaluated:

* Logistic Regression
* Random Forest

## Results

| Model               | Accuracy | Precision | Recall | F1-Score |
| ------------------- | -------: | --------: | -----: | -------: |
| Logistic Regression |   72.57% |    49.01% | 79.68% |   60.69% |
| Random Forest       |   78.39% |    62.32% | 47.33% |   53.80% |

Based on the F1-Score used in the notebook's model-selection step, Logistic Regression was selected as the final model.

## Sample Prediction

A sample customer was provided to the final model.

**Prediction: Churn = Yes**

## Project Files

```text
AI-Customer-Churn-Prediction/
│
├── README.md
├── AI_Assignment_1_Customer_Churn.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── requirements.txt
│
└── report/
    └── AI_Assignment_1_Customer_Churn_Report.pdf
```

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook

## Author

Artificial Intelligence Assignment 1
University of Lahore
