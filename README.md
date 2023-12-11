# US Housing Market Analysis

## Overview

This project aims to analyze the factors influencing the US housing market over the past 20 years and build a data science model to understand their impact on home prices. The S&P Case-Schiller Home Price Index serves as a proxy for home prices.

## Dataset

The primary dataset is sourced from the [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/) platform, focusing on key factors such as unemployment rate, GDP, income, construction data, consumer indices, and more. The dataset spans from [Specific Start Date] to [Specific End Date].

## Project Roadmap

### 1. Problem Understanding
   - Understand the problem statement and objectives.

### 2. Data Collection
   - Search for relevant blogs and resources.
   - Compile data from public websites for key factors.
```
     |- Unemployment_Rate_US_2002_2023

     |- Per_Capita_GDP_US_2003_2023

     |- Household_Income_US_2002_2023

     |- New_Constructed_Units

     |- Working_Age_Population_2022_2023

     |- Consumer_Price_Index_2002_2023

     |- Monthly_Supply_Of_New_Houses_2002_2023

     |- Building_Permits_US_2002_2023

     |- Personal_Consumption_Expenditures_Price_Index_2002_2023

     |- Delinquency_Rate_On_Credit_Card_Loans_All_Banks_2002_2023

     |- Rental_Income_Of_Persons_With_Capital_Consumption_Adjustment_In_Billions_2002_2023

     |- Employment_by Economic_Activity _Construction_2002_2023

     |- Proxy_Home_Price_Index_2002_2023 --> Dependent Variable
```

### 3. Data Preparation
   - Combine individual datasets for selected factors.
   - Handle missing values and ensure consistency.

### 4. Exploratory Data Analysis (EDA)
   - Conduct univariate, bivariate, and multivariate analysis.
   - Visualize trends and relationships in the data.

### 5. Model Building
   - Build linear regression, random forest, and XGBoost models.
   - Evaluate and compare model performance.

### 6. Feature Importance
   - Use SHAP values to explain feature importance.
   - Visualize and interpret the impact of features on home prices.

### 7. Cross-Validation
   - Assess model performance using cross-validation.
   - Compare mean CV scores for each model.

### 8. Model Selection
   - Consider various metrics (R2, MSE, etc.) for model selection.
   - Choose the best-performing model for deployment.

### 9. Model Deployment
   - Save the selected model for future use.

## Project Structure

```
├── data/
│   ├── raw_data.csv
│   └── processed_data.csv
├── notebooks/
│   ├── 01_FAUSHP_Data_Preparation.ipynb
│   ├── 02_FAUSHP_EDA_Model_Building.ipynb
│   ├── best_model.pkl
│ 
├── src/
│   ├── model.py
│   └── utils.py
├── README.md
```


## Requirements

- Python 3.x
- Google Colab Notebooks
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, SHAP

## How to Run

1. Clone the repository.
2. Install the required dependencies
3. Execute the colab Notebooks in the `notebooks/` directory in the specified order.

Feel free to reach out for any additional information or clarifications. at 📫ashishbhaidasmali@gmail.com

---
