# 🛍️ E-commerce Sales Analysis & Machine Learning Project  

This end-to-end project explores **online retail sales data** to uncover business insights, apply **machine learning models**, forecast future sales, and segment customers using **RFM analysis**.  
It demonstrates a complete **data science workflow** — from data exploration and cleaning, to predictive modeling and visual storytelling.

---

## 📑 Table of Contents
1. [Project Overview](#1-project-overview)  
2. [Data Exploration & Cleaning](#2-data-exploration--cleaning)  
3. [Exploratory Analysis](#3-exploratory-analysis)  
4. [Sales Forecasting](#4-sales-forecasting)  
5. [Customer Segmentation (RFM Analysis)](#5-customer-segmentation-rfm-analysis)  
6. [Key Insights & Business Impact](#6-key-insights--business-impact)  
7. [Dataset Source](#7-dataset-source)  
8. [How to Run This Project](#8-how-to-run-this-project)

---

## 🧭 1. Project Overview
**Dataset:** Online Retail II  
**Objective:** Analyze customer behavior, predict high-value customers, forecast sales, and segment audiences for marketing optimization.  
**Tools Used:** Python (Pandas, Matplotlib, Seaborn, Scikit-Learn)

---

## 🧹 2. Data Exploration & Cleaning
The data was cleaned in Python to remove null values, duplicates, and invalid entries.

### 🔍 Data Summary (Before Cleaning)
![Raw Data Summary](./images/Screenshot%202025-10-14%20000401.png?raw=1&v=2)

### 🧾 Sample Records
![Raw Data Sample](./images/Screenshot%202025-10-14%20000620.png?raw=1&v=2)

### 🧮 Summary Statistics (Before Cleaning)
![Data Summary Stats](./images/Screenshot%202025-10-14%20000912.png?raw=1&v=2)

### 🧮 Summary Statistics (After Cleaning)
![Cleaned Data Stats](./images/Screenshot%202025-10-14%20000931.png?raw=1&v=2)

---

## 📊 3. Exploratory Analysis

### 🌍 Top 10 Countries by Sales
![Top Countries](./images/Screenshot%202025-10-14%20001225.png?raw=1&v=2)

### 🏆 Top 10 Products by Sales
![Top Products](./images/Screenshot%202025-10-14%200012226.png?raw=1&v=2)

---

## 📈 4. Sales Forecasting

### 📅 Monthly Sales Over Time
![Monthly Sales Over Time](./images/Screenshot%202025-10-14%20001035.png?raw=1&v=2)

### 📈 Monthly Sales with Trend Line
![Trend Line](./images/Screenshot%202025-10-14%20001059.png?raw=1&v=2)

### 🔮 Monthly Sales Forecast (Next 6 Months)
![Sales Forecast](./images/Screenshot%202025-10-14%200012319.png?raw=1&v=2)

---

## 👥 5. Customer Segmentation (RFM Analysis)

### 🧾 RFM Table (Sample)
![RFM Table](./images/Screenshot%202025-10-14%20013756.png?raw=1&v=2)

### 📊 RFM Segment Summary
![RFM Segment Summary](./images/Screenshot%202025-10-14%20013902.png?raw=1&v=2)

### 📉 Customers by RFM Segment
![Customers by RFM Segment](./images/Screenshot%202025-10-14%20013923.png?raw=1&v=2)

---

## 💡 6. Key Insights & Business Impact

| Segment | Customers | Avg Monetary (£) | Description |
|----------|------------|------------------|--------------|
| **Champions** | 1207 | 5477 | Frequent, high-spending customers — retain with loyalty rewards. |
| **Loyal Customers** | 1075 | 1307 | Consistent buyers — ideal for upselling and cross-selling. |
| **Potential Loyalists** | 1109 | 544 | Promising customers — nurture with discounts and engagement. |
| **At Risk** | 719 | 255 | Previously active customers — re-engage with win-back offers. |
| **Lost** | 202 | 143 | Least active — reactivation or remove from high-cost campaigns. |

---

## 📚 7. Dataset Source
The dataset used in this project is **Online Retail II**, available from the  
👉 [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)

---

## ⚙️ 8. How to Run This Project

### 🧩 Prerequisites
- Python 3.10+  
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `statsmodels`

### ▶️ Steps
```bash
# 1. Clone the repo
git clone https://github.com/<your-username>/ecommerce-sales-analysis-ml.git
cd ecommerce-sales-analysis-ml

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the notebook
jupyter notebook Ecommerce_Sales_Analysis.ipynb
