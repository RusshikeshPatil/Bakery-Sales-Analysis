# 🍞 Bakery Sales Analysis using Python

## 📌 Project Overview
This project performs an end-to-end analysis of bakery sales data using Python.
The objective is to understand customer purchasing behavior, identify top-selling
products, analyze time-based sales trends, and generate actionable business insights.

## 🧰 Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## 📂 Dataset
The dataset contains transactional bakery sales data with the following fields:
- Transaction Number
- Item Name
- Quantity
- Price
- Date & Time
- Day Type (Weekday / Weekend)
- Daypart (Morning / Afternoon / Evening)

## 🧹 Data Cleaning & Feature Engineering
- Converted DateTime column to proper datetime format
- Created a new `Sales` column (Quantity × Price)
- Checked for missing and inconsistent values

## 📊 Exploratory Data Analysis (EDA)
The following analyses were performed:
- Top 10 selling products by quantity
- Sales distribution by daypart
- Daily sales trend analysis
- Weekday vs Weekend sales comparison

## 📌 Key Insights
- Coffee is the highest selling product
- Afternoon time generates maximum sales
- Weekday sales outperform weekend sales
- Sales show noticeable daily fluctuations

## 📈 Visualizations
All charts are created using Matplotlib and stored in the `visuals/` folder.

## 📄 Report
A detailed PDF report containing code explanations, visualizations, KPIs,
and conclusions is available in the `report/` folder.

## 🚀 Conclusion
This project demonstrates the complete data analysis workflow including
data loading, cleaning, visualization, insight generation, and professional
report creation using Python.
