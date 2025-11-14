E-Commerce-Sales-Analysis

Project Overview
- Project Title: E-Commerce Sales Analysis
- Dataset: Sample Superstore (Retail Orders Dataset)
- Purpose: Analyze sales, profit, discounts, and customer behavior to uncover meaningful retail insights
- Tools Used: Python, Jupyter Notebook, pandas, numpy, matplotlib, seaborn, plotly

![images](https://github.com/user-attachments/assets/bdb19022-65d7-473c-b7b5-88b35cb6287b)


This project ingests the Sample Superstore dataset, cleans and transforms it using pandas, engineers new features, and performs exploratory analysis to answer key business questions regarding profitability, product performance, and regional trends.

---------------------------------------------------------------------

Project Steps

1. Set Up the Environment
- Use Jupyter Notebook or VS Code with Python
- Create structured folders: /data, /notebooks, /reports, /plots
- Goal: Maintain a clean, organized, and reproducible workflow


2. Load the Dataset
- Source: Sample Superstore dataset (commonly used for Tableau retail analysis)
- Store dataset inside the data/ directory
- Load the CSV using pandas.read_csv()
- Validate successful data ingestion with df.head()


3. Install Required Libraries
- Install necessary Python libraries:
  pandas
  numpy
  matplotlib
  seaborn
  plotly
- Install via:
  pip install pandas numpy matplotlib seaborn plotly


4. Initial Data Exploration
- Purpose: Understand the structure and quality of the dataset
- Perform basic exploratory checks:
  Preview first rows using df.head()
  Inspect data types with df.info()
  Review summary statistics using df.describe()
  Check for missing values
  Identify duplicate rows
  Spot anomalies in sales, profit, or discount fields


5. Data Cleaning
- Remove duplicate rows to prevent inaccurate calculations
- Handle missing values appropriately (drop or impute)
- Convert data types (e.g., date columns to datetime, numeric columns to float/int)
- Clean currency and numeric formatting using .str.replace()
- Standardize text formatting in categorical fields
- Revalidate the DataFrame structure and statistics after cleaning


6. Feature Engineering
- Create new derived columns:
  Total Sales = Sales * Quantity
  Profit Margin = Profit / Sales
  Year, Month, Quarter extracted from the date column
- Purpose: Improve trend analysis and allow richer aggregations


7. Exploratory Data Analysis (EDA)
- Explore key business questions:
  Which categories generate the most revenue?
  Which regions are most profitable?
  How do discounts affect profitability?
  Which customer segments contribute most to sales?
  Which sub-categories consistently underperform?
- Use visualizations to reveal patterns:
  Bar charts for category and region comparisons
  Line charts for monthly or yearly trends
  Scatter plots for discount vs. profit relationships
  Heatmaps for correlation analysis
  Boxplots for outlier identification


8. Insights and Business Findings
- Key insights discovered:
  Technology and Office Supplies often show highest profitability
  Furniture frequently suffers from losses due to heavy discounting
  The West region tends to outperform others across most metrics
  High discounting strongly correlates with negative profit margins
  Some high-sales items have surprisingly low profit margins
- Business recommendations:
  Reduce excessive discounting in low-margin categories
  Optimize inventory based on regional demand and seasonal trends
  Focus marketing efforts on high-profit, high-growth product segments
  Reevaluate pricing and discount strategies for underperforming categories


Future Work
- Build a Tableau, Power BI, or Plotly dashboard
- Incorporate additional datasets (returns, shipping cost, customer lifetime value)
- Automate the analysis pipeline
- Apply forecasting models for predicting future demand and sales trends


Acknowledgments
- Dataset Source: Sample Superstore (Tableau Public Sample Dataset)
- Inspiration: Retail analytics workflows focused on sales optimization, profitability, and customer segmentation
