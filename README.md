# Influencer Marketing ROI Analysis

This project simulates a real-world consulting scenario: evaluating whether a $15,000 influencer marketing campaign generated meaningful return on investment (ROI). Using a synthetic but realistic dataset, I analyze individual influencer performance, uncover cost inefficiencies, and provide actionable recommendations to improve future campaign results.

## Objective

- Assess ROI for each influencer based on reach, engagement, conversion, cost, and revenue
- Identify high-efficiency and low-efficiency spend areas
- Recommend which influencers to keep, test, or drop
- Provide visual and strategic insights for stakeholder decision-making

## Dataset

The dataset was synthetically generated and includes the following fields:

- `followers`, `reach`, `engagement_rate (%)`
- `clicks`, `conversion_rate (%)`, `conversions`
- `CPC ($)`, `cost ($)`, `revenue_per_conversion ($)`
- `revenue ($)`, `ROI`

Total simulated spend: approximately $15,000  
Total influencers: 50

## Analysis Steps

1. Data Loading and Exploration  
2. Summary Statistics and Distribution Analysis  
3. ROI Visualization (Histogram + Boxplot)  
4. Top & Bottom Influencer Report  
5. Spend vs ROI Scatter Plot (Efficiency Map)  
6. Strategic Recommendations Framework  
7. Final Takeaways and Action Plan

## Visuals

All charts and visuals are saved under the `/visuals/` folder and include:
- ROI Distribution Histogram
- ROI Boxplot
- Spend vs ROI Efficiency Map

## Report

A client-ready consulting report is included in `/reports/` and outlines:
- Executive Summary
- Objective
- Data Overview
- Visual Insights
- Strategic Recommendations
- Action Plan

## Tools Used

- Python (Pandas, NumPy)
- Data Visualization: Seaborn, Matplotlib
- Environment: Jupyter Notebook (VS Code on Mac)
- Output Format: Markdown, Google Docs, PNG
