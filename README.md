# PowerBI-ScoreCard-Model-Dashboard
An interactive Power BI dashboard for monitoring score card models using metrics like Gini coefficient, PSI, CSI, and bad rate. Enables quarter-wise analysis, variable stability tracking, and visual insights for model performance evaluation.

# ScoreCard Model Monitoring Dashboard – Power BI

## Overview
This project provides an interactive Power BI dashboard to evaluate and monitor score card model performance using KPI's. The dashboard is designed for retail underwriting teams, risk analysts, and data scientists in the banking and financial services domain.

## Features
- PSI (Population Stability Index) for population shift monitoring across development and out-of-time (OOT) datasets.
- CSI (Characteristic Stability Index) for variable-level monitoring.
- Gini Coefficient calculation using AUROC method for each quarter.
- Bad Rate visualization across Score Bands and also overall bad rate per quarter.
- Slicer-enabled dynamic filtering (Quarter, Variable Name).
- Quarter-wise comparisons with model development vs. out-of-time (OOT) datasets.

## Tools Used
- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Excel** (as data source)


## Key Metrics
- **PSI**: Detects the shift in distribution between two different populations over time.
- **CSI**: Detects data drift and stability at variable level.
- **Gini Coefficient**: Evaluates model’s ability to distinguish good vs. bad customers.
- **Bad Rate**: % of defaults in the dataset.

## Business Use Case
Retail lending institutions rely on score card models to automate loan approval. However, over time, these models may degrade due to changes in customer behavior or economic factors. This dashboard helps:
- Monitor changes in customer profiles or model input variables.
- Ensure model predictions remain consistent and stable over time.
- Trigger revalidation if instability is detected.

## Sample Visuals
Screenshots of the dashboard can be found in the `Screenshots/` folder.

## Author
**Ramya Chinnari**  
Internship Project | ICICI Bank  
Department of Electronics & Communication Engineering, NIT Raipur
