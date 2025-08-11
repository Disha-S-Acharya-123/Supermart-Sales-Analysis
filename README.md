README – Supermart Analysis (Jupyter Notebook)

Problem Statement:
The Supermart dataset contains scattered sales data across multiple categories, 
making it difficult to quickly identify performance trends. Without proper analysis, decision-making for inventory, 
pricing, and marketing strategies becomes inefficient.

1. Notebook Overview
The analysis.ipynb file contains Python-based data analysis of the Supermart Analysis dataset. 
It uses data manipulation, aggregation, and visualization techniques to explore:
sales performance, product trends, and profitability.

2. Purpose
The purpose of this notebook is to:
Clean, preprocess, and analyze the dataset.
Identify trends and patterns in sales.
Calculate key performance indicators (KPIs) like total sales, profit margin, and category performance.
Create visualizations for better insight into the data.

3. Structure
The notebook includes the following sections:
Importing Libraries – Loading necessary Python packages.
Data Loading – Reading the Excel dataset into a DataFrame.
Data Cleaning – Handling missing values and correcting inconsistencies.
Exploratory Data Analysis (EDA) – Summarizing and visualizing the data.
Insights & Findings – Highlighting important trends and patterns.
Conclusion – Summary of the analysis.

4. Steps Followed in Analysis
Imported dataset into Pandas DataFrame.
Deleted Few values in the columns: Country, Postal Code, and in Category.
Created null values to apply automation in Python.
Checked data types and handled missing values.
Created new calculated columns (e.g., Profit Margin, Total Revenue).
Grouped and aggregated data by relevant dimensions (e.g., Category, Region).
Plotted charts such as bar graphs, pie charts, and line graphs using Matplotlib/Seaborn.
Interpreted results to identify key insights.

5. Usage Instructions
Open the .ipynb file in Jupyter Notebook, JupyterLab, or VS Code with Python support.
Run the cells sequentially to reproduce the analysis.
Modify file paths in the loading section if your dataset is stored in a different location.
Ensure required Python libraries are installed (Pandas, NumPy, Matplotlib, Seaborn).

6. Notes
Compatible with Python 3.x.
Analysis is for internal purposes and should not be distributed externally without approval.

Conclusion: 
The analysis revealed clear sales trends, identified top-performing categories, 
and highlighted areas with low profitability. These insights can guide better inventory planning, 
targeted promotions, and improved discount strategies.

