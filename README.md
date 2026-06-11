# LendingClub — Default Prediction
EDA and default prediction on loans using SQL, Python and MLflow


## Overview
End-to-end data project analyzing loan default risk using LendingClub data (2010–2018).  
The goal is to identify the key drivers behind loan defaults using EDA and Machine Learning.

## Tools & Technologies
- **SQL** — Data cleaning and exploration (DuckDB + SQL Magic in Google Colab)
- **Python** — EDA and data visualization (Pandas, Matplotlib, Seaborn)
- **Power BI** — Interactive dashboard with KPIs
- **MLflow** — Experiment tracking for ML models *(coming soon)*

## Key Findings
- Grade G loans have a **50.3% default rate** vs 5.7% for Grade A
- Small business loans show the **highest default rate** (30.2%)
- Defaulted borrowers have higher DTI (20.14 vs 17.85) and lower income ($72k vs $79k)
- Employment length shows **no significant impact** on default rate

## Dashboard
![Dashboard](lending_club_dashboard.jpeg)

## Project Structure

## Next Steps
- Train ML models (Logistic Regression, Random Forest, XGBoost)
- Track experiments with MLflow
