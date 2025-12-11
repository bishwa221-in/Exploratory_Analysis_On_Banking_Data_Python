📌 **Project Title**
Advanced Dataframe Operations – Banking Dataset Analysis

📘 **Project Overview**
-This project demonstrates end-to-end exploratory data analysis (EDA) on banking datasets.
-Multiple datasets (Accounts, Customers, Transactions) were merged to create a unified analytical view.
-The notebook performs cleaning, merging, aggregations, pivot tables, visualizations, and behavioral insights.

📂 **Files in This Repository**

📓 Exploratory_Analysis_On_Banking_Data.ipynb
The main Jupyter Notebook containing all analysis, transformations, and visualizations.

📄 Exploratory_Analysis_On_Banking_Data.pdf
A presentation-style summary of the key findings and insights from the analysis.

📊 **Key Insights & Analysis Performed**
1. Data Preparation
-Loaded Accounts, Customers, and Transactions datasets
-Cleaned and merged them to create a unified master dataframe
-Performed datatype fixing, date formatting, and feature creation

2. Customer & Regional Insights
-Customer distribution across regions
-Region × Occupation relationship using groupby and pivot tables
-Visualized with heatmaps and bar charts

3. Account Type Performance
-Transaction count, total amount, and average amount for each account type
-Channel usage patterns (ATM, Online, Branch)
-Account type × transaction channel heatmap

4. Account Closure & Tenure
-Status comparison (Open vs Closed)
-Tenure calculation for closed accounts
-Identified trends related to customer churn

5. Transaction Trend Analysis
-Month-wise transaction volume and amount
-Identified top months with highest activity
-Distribution analysis for outliers and skew

📈 **Visualizations**
The types of charts used:
-Heatmaps
-Barplots
-Distribution plots
-Pivot table summaries

This helps viewers understand the analytical depth.

🛠️ **Technologies Used**
-Python
-Pandas, NumPy
-Matplotlib, Seaborn
-Jupyter Notebook

🚀 **How to Run This Project**
Basic instructions:
1. Clone the repository  
2. Install required libraries  
3. Open the notebook in Jupyter  
4. Run cells step-by-step to reproduce the analysis

📌 **Use Cases of This Project**
-Banking customer segmentation
-Understanding transaction behaviour
-Account type performance analysis
-Monthly revenue insights
-Churn prediction foundation
