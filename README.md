# starbucks-rewards-analytics
Data engineering and customer behaviour analysis using Starbucks app rewards dataset. Ingested and transformed data on Azure; performed segmentation and campaign recommendation using SQL.


# Starbucks Rewards Analytics

This project explores customer behaviour in the Starbucks Rewards Program using data engineering techniques on Azure and SQL. It covers the full pipeline: ingestion of raw JSON data, transformation, analysis, and marketing campaign recommendations.

## 📁 Project Structure

- `data/raw/`: Raw JSON files (zipped due to GitHub size limits)  
  → [`starbucks-raw-data.zip`](./data/raw/starbucks-raw-data.zip)
- `data/processed/`: Cleaned and transformed CSV outputs for analysis
- `sql/`: SQL scripts for ingestion, transformation, and analysis (Parts 1–4)
- `reports/`: Business insights, tables, and campaign recommendations
- `assets/`: Charts and visuals used in reports or this README

## 🛠 Tools & Techniques

- Azure SQL Database with external table ingestion
- SQL for data transformation, feature engineering, and aggregation
- Customer segmentation by age group
- Spend analysis and offer engagement metrics

## 📊 Key Insights

- Identified top 5 customers by total spend and transaction behaviour
- Segment-specific trends across income, offer completion, and rewards earned
- Estimated ROI based on different campaign completion rates (25%, 50%, 75%)

## 🎯 Business Recommendation

Built an optimised marketing campaign recommendation for each age group, based on behavioural trends and offer responses. Final report includes visual support and cost estimations.

## 📦 Dataset

The original dataset includes:
- `portfolio.json` – Offer types, durations, and delivery channels
- `profile.json` – Demographics including age, income, and gender
- `transcript.json` – All customer interactions (offers received, viewed, completed, and transactions)

Source: [Kaggle – Starbucks Customer Reward Program](https://www.kaggle.com/datasets/blacktile/starbucks-app-customer-reward-program-data)

Note: Raw files are provided as a zip due to GitHub’s 25MB file limit. See `data/raw/starbucks-raw-data.zip`.

