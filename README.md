# Customer Churn Prediction Using ANN

## Problem Statement
Customer churn is a major business challenge for telecom companies. The goal of this project is to predict whether a customer will leave the service (churn) using customer profile and usage information.

## Approach
This project uses an Artificial Neural Network (ANN) for binary classification:
- Input: customer features after preprocessing and encoding
- Hidden layers: 2 dense layers with ReLU activation
- Output: 1 neuron with Sigmoid activation for churn probability

## Key Features
- End-to-end churn prediction workflow in one clean notebook
- Data preprocessing and feature engineering
- ANN model training and evaluation
- Output includes:
  - churn probability
  - risk category: Low / Medium / High
  - short explanation based on tenure and monthly charges

## Dataset
- Source: Telco Customer Churn Dataset (Kaggle)
- Link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Note: For clean GitHub repositories, prefer sharing the dataset link instead of uploading large raw data files.

## Technologies Used
- Python
- NumPy
- pandas
- matplotlib
- seaborn
- scikit-learn
- TensorFlow / Keras

## How to Run
1. Clone the repository.
2. Install dependencies:
   - `pip install -r requirements.txt`
3. Open the notebook:
   - `Customer_Churn_ANN_Clean.ipynb`
4. Run cells from top to bottom.

## Output
The notebook reports:
- Model accuracy
- Confusion matrix
- Classification report
- Accuracy and loss curves
- Sample customer predictions with risk level and simple reasons

## Repository Structure (Recommended)
- `Customer_Churn_ANN_Clean.ipynb`
- `README.md`
- `requirements.txt`
- Optional: small sample data file or dataset link in README

## Author
Rupesh (Deep Learning Project - Academic + Portfolio)
