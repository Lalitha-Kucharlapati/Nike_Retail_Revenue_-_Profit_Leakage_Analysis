# Nike Sales Analysis – Revenue, Profit & Discount Insights

## 📌 Project Overview
This project analyzes Nike sales data to uncover insights related to revenue leakage, profit/loss patterns, discount impact, and customer behavior across regions, product lines, and sales channels. The project focuses on **business-driven data analysis**, not machine learning.

## 🎯 Business Objectives
- Identify profit and loss trends across products and regions
- Analyze the impact of discounts on revenue and profit
- Detect revenue gaps caused by zero or negative sales
- Understand customer purchase patterns by gender, size, and category
- Build an interactive Power BI dashboard for decision-making

## 📊 Dataset
- **Source:** Nike_Sales_Uncleaned.csv
- **Records:** ~2500 rows
- **Key Columns:**
  - Order_ID
  - Gender_Category
  - Product_Line
  - Product_Name
  - Size / Size_Apparel
  - Units_Sold
  - MRP
  - Discount_Applied
  - Revenue
  - Profit
  - Order_Date
  - Sales_Channel
  - Region

## 🛠 Data Cleaning & Feature Engineering
Performed using Python (Pandas):
- Handled missing and inconsistent values
- Standardized size values into apparel categories (S, M, L, XL)
- Created derived metrics:
  - Discount Rate
  - Expected Revenue
  - Revenue Gap
  - Profit Margin
  - Loss Flag
  - Month & Year

Cleaned dataset was exported for visualization.

## 📈 Power BI Dashboard
Built an interactive Power BI dashboard including:
- Revenue & Profit Overview
- Profit vs Loss Analysis
- Revenue Gap Analysis
- Sales by Region & Channel
- Product Line & Size-wise Performance
- Monthly & Yearly Trends
- Filters for Gender, Region, Channel, Product Line

## 📂 Project Structure
Nike_Retail_Revenue_&_Profit_Leakage_Analysis/
│
├── data/
│ ├── Nike_Sales_Uncleaned.csv
│ └── Nike_Sales_Cleaned.csv
│
├── notebook/
│ └── nike_sales_data_cleaning.ipynb
│
├── powerbi/
│ └── Nike_Sales_Analysis.pbix
│
├── requirements.txt
└── README.md

## 🚀 Tools & Technologies
- Python (Pandas, NumPy)
- Power BI
- Jupyter Notebook
- Git & GitHub

## 💡 Key Insights
- Significant revenue leakage due to zero or negative recorded sales
- High discounts do not always correlate with higher profit
- Certain regions and product lines consistently generate losses
- Size and gender-based demand patterns influence profitability

## 📌 Conclusion
This project demonstrates **real-world data analyst skills**, including data cleaning, business metric creation, and dashboard storytelling using Power BI.
