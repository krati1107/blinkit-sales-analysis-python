# 🛒 Blinkit Sales Analysis Using Python

## 📌 Project Overview
This project focuses on analyzing Blinkit's sales performance, product categories, customer ratings, and outlet performance using Python.

The objective is to explore sales data, identify important business trends, calculate Key Performance Indicators (KPIs), and generate meaningful business insights through data analysis and visualization.

## 🎯 Project Objectives
- Analyze overall sales performance.
- Understand sales distribution across different item types.
- Compare sales by fat content.
- Analyze outlet-wise sales performance.
- Evaluate sales by outlet size and location.
- Understand customer ratings.
- Identify patterns and provide data-driven business recommendations.

## 🛠️ Technologies & Libraries Used
- Python
- Google Colab
- Pandas – Data Cleaning and Manipulation
- NumPy – Numerical Analysis
- Matplotlib – Data Visualization
- Seaborn – Statistical Visualization

## 📂 Dataset Information
- Total Records: 8,523
- Total Columns: 12
- Dataset Format: CSV

The dataset contains information about:
- Item Identifier
- Item Type
- Item Fat Content
- Item Weight
- Sales
- Rating
- Outlet Identifier
- Outlet Establishment Year
- Outlet Size
- Outlet Location Type
- Outlet Type

## 🔍 Project Workflow

### 1. Data Loading
Imported the dataset into Python using Pandas.

### 2. Data Cleaning
- Checked missing values.
- Handled missing Item Weight values using median imputation.
- Checked duplicate records.
- Standardized inconsistent Fat Content categories.

### 3. Exploratory Data Analysis (EDA)
Performed exploratory analysis to understand the dataset, distributions, and sales patterns.

### 4. KPI Analysis
Calculated:
- Total Sales
- Average Sales
- Number of Item Records
- Average Customer Rating

### 5. Data Visualization
Created visualizations using Matplotlib and Seaborn:

1. Total Sales by Fat Content – Donut Chart
2. Total Sales by Item Type – Bar Chart
3. Fat Content by Outlet – Stacked Column Chart
4. Total Sales by Outlet Establishment Year – Line Chart
5. Sales by Outlet Size – Pie Chart
6. Sales by Outlet Location – Bar Chart

### 6. Business Insights
Analyzed:
- Top-performing item categories.
- Outlet-wise sales performance.
- Sales contribution by location.
- Fat-content sales distribution.
- Customer rating patterns.
- Correlation between numerical variables.

## 💡 Business Value
This analysis can help businesses understand product performance, compare outlet sales, identify sales patterns, and make better product assortment and operational decisions.

## 📁 Project Files
- `Blinkit_Sales_Analysis_Python.ipynb` – Complete Python analysis notebook.
- `blinkit_data.csv` – Original dataset.
- `Blinkit_Cleaned_Data.csv` – Cleaned dataset (generated after running the notebook).

## 🚀 How to Run This Project
1. Download or clone this repository.
2. Open the `.ipynb` notebook using Google Colab.
3. Upload the original CSV dataset when prompted.
4. Run all cells sequentially.
5. Explore the analysis, visualizations, and business insights.

## 📌 Conclusion
This project demonstrates the use of Python for data cleaning, exploratory data analysis, KPI calculations, statistical analysis, and data visualization to solve a real-world retail sales analysis problem.

---

**Project Category:** Data Analytics  
**Created Using:** Python  
**Environment:** Google Colab
