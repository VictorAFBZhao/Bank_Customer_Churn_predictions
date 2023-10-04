# Customer Churn Analysis Project

Data - https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset/data
## Overview

This project aims to perform customer churn analysis using Python. Customer churn, also known as customer attrition, is the rate at which customers stop doing business with a company. In this project, we use a dataset containing customer information to analyze and gain insights into factors that may influence churn.

## Dataset

The dataset used for this analysis contains the following columns:

- `customer_id`: Unique identifier for each customer.
- `credit_score`: Credit score of the customer.
- `country`: Customer's country.
- `gender`: Customer's gender.
- `age`: Customer's age.
- `tenure`: Number of years the customer has been with the company.
- `balance`: Customer's account balance.
- `products_number`: Number of products the customer has.
- `credit_card`: Whether the customer has a credit card (1 for yes, 0 for no).
- `active_member`: Whether the customer is an active member (1 for yes, 0 for no).
- `estimated_salary`: Estimated salary of the customer.
- `churn`: Churn status (1 for churned, 0 for not churned).

## Analysis

### Exploratory Data Analysis (EDA)

- Summary statistics of numeric columns.
- Count of unique countries and genders.
- Probabilities of churn based on gender, credit card ownership, and active membership.
- Correlation analysis between numeric variables.

### Hypothesis Testing

- Performed a hypothesis test to determine if there is a statistically significant difference in age between customers who churned and those who stayed.

### Sampling

- Created a random sample of the data for analysis purposes.

### Estimation and Inference

- Estimated the mean of estimated salary with a 95% confidence interval.

### Churn Analysis by Country

- Analyzed the churn rate based on the country of the customers to identify differences in churn rates among countries.

## Dependencies

- Python 3.x
- pandas
- numpy
- scipy
- matplotlib

## Usage

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install pandas numpy scipy matplotlib`.
3. Run the Python scripts for the specific analyses you want to perform.

## Conclusion

This project provides insights into customer churn based on the provided dataset. The analyses and visualizations help in understanding factors that may influence churn and making data-driven decisions for customer retention and business strategies.

For more details or additional analyses, feel free to customize the code and explore further insights.
