# Medical Data Feature Engineering

## Overview
This project focuses on preparing a healthcare dataset for machine learning by applying a complete feature engineering pipeline.

## Dataset
- Rows: 929,107
- Columns: 108
- Contains numerical, categorical, and temporal features

## Key Steps
- Data Cleaning (duplicates, missing values)
- Feature Transformation (scaling, encoding)
- Feature Engineering (date features, interactions)
- Feature Selection (top 70 features)

## Target Variable
LDL Cholesterol

## Results
- Final Features: 70
- Training Records: 253,784
- Testing Records: 63,446

## Files
- `notebook.ipynb` → Full pipeline
- `Feature_Engineering_Report.pdf` → Project report

## Notes
All preprocessing was done after train-test split to prevent data leakage.
