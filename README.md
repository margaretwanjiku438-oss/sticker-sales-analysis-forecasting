# Sticker Sales Analysis & Forecasting

## Project Overview

This project analyzes historical sticker sales data across different countries, stores, products, and time periods. The goal was to explore sales patterns, investigate data quality, identify useful business insights, and build a baseline forecasting model.

## Objectives

* Inspect and assess the quality of the sales data
* Investigate missing values and understand their patterns
* Analyze sales performance across countries, products, and stores
* Identify yearly and monthly sales patterns
* Prepare the data for time-series forecasting
* Build and evaluate a baseline forecasting model

## Tools & Technologies

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Key Analysis Areas

### Data Quality

The dataset was checked for:

* Missing values
* Duplicate records
* Duplicate date-country-store-product combinations
* Date continuity
* Missing sales values across countries, products, stores, and years

The analysis found that missing sales values were not randomly distributed, with a particularly high proportion of missing values associated with the Holographic Goose product.

### Exploratory Data Analysis

Sales were analyzed across:

* Countries
* Products
* Stores
* Years
* Months

The analysis identified differences in sales performance across these dimensions and highlighted seasonal and business-level patterns in the data.

### Forecasting

A monthly seasonal baseline was created using historical average sales for each calendar month.

The model was evaluated using a 2016 validation period.

**Validation results:**

* MAE: 8,332.97
* RMSE: 9,134.91
* MAPE: 14.76%

The baseline provides a useful starting point for forecasting, while the comparison between actual and predicted sales shows that the model captures broad monthly patterns but does not fully capture daily fluctuations.

## Project Workflow

The project followed a practical data-analysis workflow:

**Inspect → Investigate → Clean → Analyze → Forecast → Evaluate → Communicate**

## Files

* `sticker_sales_analysis.ipynb` — Main analysis notebook
* `requirements.txt` — Python packages used in the project
* `images/` — Selected visualizations from the analysis
* `data/README.md` — Information about the dataset source

## Dataset

The dataset is based on the Kaggle Playground Series Sticker Sales dataset.

The original dataset is not included in this repository.

## Conclusion

This project demonstrates a complete beginner-to-intermediate data analysis workflow, from data-quality investigation and exploratory analysis to time-series preparation, baseline forecasting, and model evaluation.

