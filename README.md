# SaaS Revenue Health Engine

This project analyzes the revenue health of a SaaS company by breaking down Monthly Recurring Revenue (MRR) into different parts and finding where the company is growing or losing money.

## Why I built this

Most SaaS companies only look at total MRR. But total MRR can be misleading. Even if the number is going up, the company might be losing existing customers at the same time. I wanted to build something that shows the real picture.

## What this project does

- Breaks MRR into New, Expansion, Contraction, and Churned
- Calculates Net New MRR and Quick Ratio every month
- Compares performance across different plans (Basic, Pro, Enterprise)
- Compares performance across industries
- Finds the main reasons why customers are churning
- Creates a clean Power BI dashboard for easy understanding

## Tools I used

- Python (Pandas)
- Jupyter Notebook
- Power BI

## Main Findings

- Enterprise customers bring the most expansion revenue, but they also cause the highest revenue loss when they leave.
- FinTech and HealthTech are the strongest industries.
- Cybersecurity and DevTools have high expansion but also high churn.
- The biggest reason customers leave is missing features, followed by support issues and budget problems.

## Project Structure

- `RavenStack Analysis.ipynb` → Full analysis
- `SaaS Dashboard.pbix` → Power BI dashboard
- `mrr_movement.csv`
- `plan_summary.csv`
- `industry_summary.csv`
- `churn_reason_summary.csv`

## Dashboard

The Power BI dashboard has 3 pages:

1. Executive Overview
2. Segment Performance
3. Churn Analysis

## Skills used

- Data Cleaning
- Data Analysis
- Python (Pandas)
- Power BI
- Business Thinking

## Author

Bhaskar Kashyap
