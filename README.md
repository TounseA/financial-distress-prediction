# Predicting Financial Distress Using ML
The prediction of company financial failure is of interest to investors. In this project, the plan is to **employ a number of ML techniques** to the problem of predicting bankruptcy. A set of features need to be identified. The accuracy of **each method should be calculated and compared**.

## Project Overview 
The models tested in this project are the following:
- Altman Z-Score (baseline)
- Logistic Regression 
- Random Forests 
- Neural Networks
- XGBoost

### Dataset Desciption
To ensure fair and consistent evaluation, all final versions of models use the same dataset.

The dataset, US Company Bankruptcy Prediction Dataset, includes financial data for public companies listed on the NYSE and NASDAQ (1999–2018). Key details:
- 8,262 distinct companies
- 78,682 observations (firm-year combinations)

Key financial features included in dataset:
- Current Assests (X1)
- Cost Of Goods Sold (X2)
- Depreciation and Amortization (X3)
- ...and more (see the Notebook for full attribute list description).

Bankruptcy is labeled as:

- 1: If the company files for Chapter 11 (reorganization) or Chapter 7 (liquidation).
- 0: If the company operates normally.

#### Dataset Source:

The dataset is publicly available on Kaggle. You can find it [here](https://www.kaggle.com/datasets/utkarshx27/american-companies-bankruptcy-prediction-dataset).

## How To Run
Requirements:

- Python 3.x

Libraries: `pandas`, `numpy`, `matplotlib`, and `scikit-learn`

Steps:

Open the notebook file: `FD_V2.ipynb`. 

Run it using any notebook environment (e.g., Jupyter, Google Colab, etc.).

