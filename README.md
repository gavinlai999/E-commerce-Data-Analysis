E-Commerce-Sales-Analysis
Project Overview

Project Title: E-Commerce Sales Analysis
Database: Sample Superstore Dataset

![images](https://github.com/user-attachments/assets/6176b9a0-8752-4d04-b379-7c8fbe3dc29f)


This project ingests e-commerce sales data, cleans and analyzes it using pandas, and runs targeted exploratory analysis to answer business questions. It’s a practical walkthrough of data wrangling, EDA, feature engineering, and visualization in one notebook.
Project Steps
1. Set Up the Environment

Tools Used: Jupyter Notebook, Python
Goal: Build a clean environment to support structured analysis, organized workflow, and reproducible code execution.

2. Load the Dataset

Source: Sample Superstore dataset (commonly used for Tableau and retail analytics tasks)
Storage: Place the dataset inside a data/ folder or load directly into your notebook

3. Install Libraries

Install necessary Python libraries for processing and visualization:

pip install pandas numpy matplotlib seaborn plotly

4. Import & Inspect the Data

Goal: Conduct a first-pass scan of the dataset
Analysis Tools:

df.head() — preview rows

df.info() — check schema

df.describe() — review statistical ranges

Detect duplicates, anomalies, and inconsistent values

5. Data Cleaning

Key cleaning steps include:

Remove duplicates to avoid inaccurate totals

Handle missing values (drop or impute based on importance)

Normalize data types (dates → datetime, numeric → float/int)

Standardize currency/number formatting using .str.replace()

Revalidate dataset after cleaning to ensure consistency

6. Exploratory Data Analysis (EDA)

Tasks performed:

Sales and profit trends across categories

Performance comparison by region and segment

Discount impact on profit

Identification of high-loss categories

Visualizations using matplotlib/seaborn/plotly to highlight patterns

7. Feature Engineering

New derived fields include:

Total Sales per order

Profit Ratio / Margin

Year, Month, Week Extracted Columns for time-based analyses
Purpose: Enable clearer aggregations and better trend analysis

8. Business Questions & Insights

Analysis covered:

Top-performing product categories

Which regions drive the highest profit

Patterns in customer segments

Times of peak sales

Categories hurt most by discounting

A separate log (e.g., reports/analysis.md) can track each question, method, and conclusion.

Future Work

Build a Tableau/Power BI dashboard for interactive visualizations

Incorporate additional retail datasets to enhance depth of analysis

Automate the notebook → dashboard workflow using scheduled scripts

Acknowledgments

Dataset: Sample Superstore Dataset

Inspiration: Retail analytics case studies on sales optimization and discount strategy
