## Walmart Sales Performance Analysis
# Overview

This project analyzes historical Walmart store sales to identify performance differences across locations, seasonal trends, and the impact of external economic factors. The analysis was conducted using SQL, Python (pandas), and Excel, with a focus on producing clear, business-relevant insights.

# Dataset

Weekly sales data for multiple Walmart stores, supplemented with economic and calendar indicators.

# Key Fields

Store – Store identifier

Date – Week of sales

Weekly_Sales – Total weekly sales

Holiday_Flag – Holiday week indicator (1 = holiday, 0 = non-holiday)

Temperature, Fuel_Price, CPI, Unemployment – External factors

# Tools Used

Python (pandas, matplotlib/seaborn) – Data cleaning, analysis, visualization

SQL – Aggregation, filtering, ranking

Excel – Summary tables and charts for reporting

Jupyter Notebook – Analysis and documentation

# Requirements
```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
openpyxl>=3.0.0
xlsxwriter>=3.0.0
jupyter>=1.0.0
```

# Installation

1. Clone the repository
```bash
   git clone https://github.com/benjaminmoizer/walmart-sales-analysis.git
   cd walmart-sales-analysis
```

2. Download the dataset
   - Dataset: [Walmart Sales Data on Kaggle](https://www.kaggle.com/datasets/mikhail1681/walmart-sales)
   - Place `walmart_sales.csv` in the `data/` folder

3. Run the analysis
```bash
   jupyter notebook notebooks/walmart_analysis.ipynb
```

# Analysis Highlights

Identified top and bottom performing stores based on average weekly sales

Analyzed sales trends over time, including holiday vs non-holiday periods

Evaluated relationships between sales and macroeconomic indicators

Exported results to Excel for stakeholder-friendly reporting

# Key Insights

Store-level performance differences are substantial and persistent.

Holiday weeks generally correspond to higher average sales, though effects vary by store.

External economic variables show limited short-term influence compared to store-specific factors.
