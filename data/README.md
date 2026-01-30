# Dataset Information

This folder contains the dataset used for the Predictive Customer Analytics project.

## Dataset Used
- **Name:** Online Retail II Dataset
- **Source:** UCI Machine Learning Repository
- **Description:**  
  The dataset contains two years of real transaction data from a UK-based online retail company.  
  It includes customer purchase information such as transaction dates, quantities, prices, and customer identifiers.

## Purpose of the Dataset
The dataset is used to:
- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Create RFM (Recency, Frequency, Monetary) features
- Support baseline churn identification
- Understand customer lifetime value (CLV) concepts

## Notes
- Records with missing customer IDs are removed during data cleaning
- Invalid transactions such as negative quantities are filtered out
- Monetary value is computed using Quantity × Unit Price
