# 🛒 Blinkit Retail Sales Analysis (EDA with Python)

![Python](https://img.shields.io/badge/Python-3.10-blue.svg) 
![Pandas](https://img.shields.io/badge/Pandas-Data--Analysis-orange.svg) 
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-teal.svg) 
![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-yellow.svg) 

---

## 📌 Project Overview
This project analyzes **Blinkit grocery sales data** to extract **actionable business insights**.  
The goal is to understand product performance, outlet trends, and customer preferences through **data cleaning, EDA, KPI calculation, and visualization**.  

The notebook demonstrates **end-to-end data analysis workflow** and highlights skills valuable for **data analyst roles**.

---

## 📂 Dataset
- **File:** `blinkit_data.csv`  
- **Contents:** Sales transactions including product details (type, fat content, weight), outlet information (location, size, year), ratings, and sales performance.  
- **Note:** Dataset used for educational purposes only.  

---

## 🎯 Project Objectives
- Clean and preprocess raw retail sales data  
- Explore sales patterns by product, outlet, and customer features  
- Calculate **business KPIs** (total sales, average sales, items sold, ratings)  
- Visualize insights using Python plotting libraries  
- Provide **business recommendations** to improve strategy  

---

## ⚙️ Tools & Libraries
- **Python (Jupyter Notebook)**  
- **pandas, numpy** → Data cleaning & manipulation  
- **matplotlib, seaborn** → Statistical visualization  
- **plotly express** → Interactive charts  

---

## 📊 Key KPIs
- **Total Sales:** $1.2M+  
- **Average Sales per Item:** $141  
- **Number of Items Sold:** 8,500+  
- **Average Customer Rating:** 3.8 / 5  

---

## 🔎 Workflow Summary
1. **Data Loading & Inspection**
   - Load CSV with pandas  
   - Preview structure, columns, and stats  

2. **Data Cleaning**
   - Fix inconsistent labels (e.g., “LF” → “Low Fat”)  
   - Handle missing values (`Item Weight`, `Item Visibility`)  
   - Replace zeros with median values  

3. **Exploratory Data Analysis**
   - **Univariate analysis** (distributions, boxplots, counts)  
   - **Multivariate analysis** (grouped sales, outlet comparisons)  
   - Trend analysis by **year, region, and outlet size**  

4. **Visualization**
   - Donut charts (sales share by fat content, outlet size)  
   - Bar plots (item type sales, outlet location performance)  
   - Line plots (sales by establishment year)  
   - Stacked bars (fat content by outlet tier)  

5. **Insights & Recommendations**
   - Identify **fast vs slow-moving products**  
   - Compare **outlet tiers and regions**  
   - Highlight **benchmark outlets** for best practices  

---

## 📊 Key Insights
- **Top Item Categories:** Fruits & Vegetables, Snack Foods, Household items  
- **Top Outlets:** OUT035, OUT046, OUT013 → contribute the most sales  
- **Sales by Region:** Tier 3 outlets outperform Tier 1 & Tier 2  
- **Best Establishment Year:** 1998 outlets have the strongest long-term performance  
- **Fast Movers:** Fruits, Snacks, Household  
- **Slow Movers:** Starchy Foods, Breakfast items, Seafood  

---

## 🚀 Business Recommendations
- Allocate more inventory to **fast-moving categories** to avoid stockouts  
- Launch **promotions** for slow-moving categories to boost demand  
- Replicate successful strategies from **Tier 3 outlets** to other regions  
- Study **high-performing outlets** as benchmarks for expansion  

---

## 📂 Repository Structure
| File                                    | Description                                   |
|------------------------------------------|-----------------------------------------------|
| `Blinkit Analysis using Python.ipynb`    | Main analysis notebook                        |
| `blinkit_data.csv`                       | Dataset (if shareable)                        |
| `Blinkit_client_req.pptx`                | Business/client presentation slides           |
| `README.md`                              | Project documentation (this file)             |

---

## 🖼️ Sample Visuals
*(Add PNGs/screenshots of your charts inside an `images/` folder and link them here)*

```markdown
![Sales by Item Type](images/sales_by_item_type.png)
![Sales by Outlet Size](images/sales_by_outlet_size.png)



