# Sales / E-commerce Data Analysis using Pandas

## 📌 Project Overview
This project is an end-to-end sales data analysis using **Python and Pandas** on messy, real-world e-commerce data.  
The dataset contains missing values, duplicates, invalid entries, and inconsistent data formats.  
The goal is to clean the data, perform analysis, and generate meaningful business insights.

---

## 🎯 Problem Statement
Analyze sales data that contains:
- Missing values
- Duplicate records
- Invalid quantities and prices
- Inconsistent product and region information

After cleaning the data, generate summary reports and visualizations to understand sales performance.

---

## 📂 Dataset Description

### Raw & Cleaned Data (`data/`)
- `Sales_Ecommerce_Data.csv`  
  → Original raw dataset with inconsistencies and missing values  

- `cleaned_sales_data_1000.csv`  
  → Initially cleaned dataset (basic cleaning applied)

- `final_cleaned_sales_data_1000.csv`  
  → Fully cleaned and finalized dataset used for analysis  

---

## 🧹 Data Cleaning Steps
The following steps were performed:

1. Loaded raw CSV files using Pandas  
2. Identified missing values in key columns  
3. Filled missing numerical values using mean/appropriate logic   
4. Removed duplicate records 
5. Handled missing categorical values
6. Fixed invalid quantities (zero values)  
7. Corrected inconsistent product and region names  
8. Converted columns to proper data types  
9. Created derived columns (e.g., total sales)  
10. Validated cleaned data  
11. Saved intermediate cleaned data  
12. Created a final cleaned dataset for analysis  

---

## 📊 Analysis & Outputs

### Summary CSV Files (`outputs/`)
- `product_sales_summary.csv`  
- `region_sales_summary.csv`  
- `avg_order_per_region.csv`  
- `top_product_per_region.csv`  

These files provide aggregated insights such as:
- Total sales by product
- Revenue by region
- Average order value per region
- Top-selling product in each region

---

## 📈 Visualizations (`outputs/charts/`)
The following charts were generated and saved as PNG files:

- Total sales per product  
- Revenue contribution by region  

Charts are saved programmatically from Jupyter Notebook using `plt.savefig()`.

---

## 🗂️ Project Structure

sales-ecommerce-analysis/
├── data/
│ ├── Sales_Ecommerce_Data.csv
│ ├── cleaned_sales_data_1000.csv
│ ├── final_cleaned_sales_data_1000.csv
├── notebooks/
│ └── Sales_Ecommerce_Analysis.ipynb
├── outputs/
│ ├── product_sales_summary.csv
│ ├── region_sales_summary.csv
│ ├── avg_order_per_region.csv
│ ├── top_product_per_region.csv
│ └── charts/
│ ├── Total_sales_per_product.png
│ ├── Revenue_contribution_By_Region.png
├── README.md

---

## 🛠️ Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 🚀 How to Run the Project
1. Clone the repository  
2. Open `Sales_Ecommerce_Analysis.ipynb` in Jupyter Notebook or VS Code  
3. Run the notebook step by step  
4. Cleaned data, summary CSVs, and charts will be generated automatically  

---

## 🧠 Key Learnings
- Handling messy real-world datasets  
- Data cleaning and preprocessing  
- Aggregation and grouping using Pandas  
- Generating business insights from data  
- Saving outputs and visualizations programmatically  


