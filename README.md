# Sales Pipeline Data Analysis

## Overview
This project analyzes a **sales pipeline dataset** to extract insights into sales performance, deal status, and revenue trends. The dataset includes **sales agents, products, accounts, deal stages, and revenue details**.

## Steps Performed

### 1. **Data Loading & Exploration**
- Loaded the `sales_pipeline.csv` dataset.
- Checked the structure, missing values, and basic statistics.
- Converted `engage_date` and `close_date` into **datetime format**.

### 2. **Feature Extraction**
Extracted new insights from the dataset:
- **Top-performing sales agents** based on closed deal value.
- **Best-selling products** based on the number of deals.
- **Deal stage distribution** (Won vs. Lost vs. In Progress).
- **Sales cycle duration** (time taken to close a deal).
- **Monthly revenue trends** to understand seasonality.

### 3. **Data Visualization**
Generated multiple plots to visualize insights:
- **Bar Charts**
  - Top 10 sales agents by **total closed deal value**.
  - Top 10 products by **total sales**.
  - Top accounts by **number of deals**.
- **Pie Chart**
  - Deal stage distribution (Won, Lost, In Progress).
- **Line Chart**
  - Monthly closed deals over time.
  - Predictive trend line for future sales.
- **Histogram**
  - Sales cycle duration distribution.
- **Heatmaps**
  - Correlation matrix between revenue and sales cycle.
  - Product vs. Month revenue heatmap.
- **3D Scatter Plot**
  - Sales agent vs. Close value vs. Sales cycle duration.

### 4. **Advanced Analysis**
Performed deeper analysis to uncover insights:
- **Sales Funnel Analysis**: How deals move through different stages.
- **Revenue Forecasting**: Trend analysis for predicting future sales.
- **Sales Performance Heatmaps**: Identifying top products and peak sales months.

## Future Improvements
- Implement **Machine Learning** for sales predictions.
- Optimize **sales strategy** using AI-driven insights.
- Develop an interactive **dashboard** for real-time sales tracking.

## How to Use
1. Load the dataset into a Python environment.
2. Run the provided Jupyter notebook or Python scripts.
3. Analyze the generated plots and insights.

---
**Author:** AdwizeX 🚀 | **Tools Used:** Python, Pandas, Matplotlib, Seaborn, NumPy

