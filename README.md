# Customer Behavior Analysis for Business Decision Making

## Overview
A complete data science project analyzing customer behavior data to understand churn drivers,
segment customers, and build a predictive model that flags customers at risk of leaving.

Built as part of the RISE Internship — **Data Science & Analytics — Project 1**.

## Problem Statement
Companies collect large volumes of customer data but struggle to convert it into actionable
insights. Without proper analysis, businesses fail to understand customer behavior, preferences,
and churn risk — leading to poor decision-making and revenue loss.

## What This Project Covers
-  Customer dataset ingestion
-  Data cleaning and preprocessing (missing values, invalid entries, duplicates)
-  Exploratory Data Analysis (EDA) with visualizations
-  Customer segmentation (K-Means clustering)
-  Identification of behavior patterns
-  Basic predictive model for churn (Logistic Regression)
-  Visualization of key insights
-  Business-focused insight report with recommendations

## Files
- `Customer_Behavior_Analysis.ipynb` — the full analysis notebook
- `customer_data.csv` — sample dataset (1,000 customers, intentionally messy to practice cleaning)

## Tools / Libraries Used
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (KMeans, Logistic Regression, train/test split, metrics)
- Jupyter Notebook

## How to Run
1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/customer-behavior-analysis.git
   cd customer-behavior-analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open `Customer_Behavior_Analysis.ipynb` and run all cells (Cell → Run All)

## Key Results
- **Churn rate**: ~43% of customers in the dataset have churned
- **Model performance**: 82% accuracy, 88% precision, 67% recall on churn prediction
- **Top churn drivers identified**: low satisfaction score, high support ticket volume, low tenure
- **4 customer segments** identified via clustering, including a clearly "at-risk" group

## Business Recommendations
1. Launch a "First 90 Days" onboarding/retention program for new customers
2. Improve customer support resolution speed and quality
3. Use the model's churn probability scores to prioritize retention outreach
4. Target the at-risk customer segment with personalized re-engagement campaigns

## Possible Improvements
- Try more powerful models (Random Forest, XGBoost) to improve recall
- Add more features (e.g. complaint text via NLP, channel of contact)
- Deploy as a simple dashboard (Streamlit) for non-technical stakeholders
- Retrain periodically on fresh data

## Author
Pragitha Deepak
