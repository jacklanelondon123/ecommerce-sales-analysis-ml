# 🛍️ E-commerce Sales Analysis & Machine Learning Project  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

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
![Top 10 Countries by Revenue](images/TOP%2010%20COUNTRIES%20BY%20REVENUE.png)


---

## 📈 4. Sales Forecasting

### 📅 Monthly Sales Over Time
![Monthly Sales Over Time](./images/Screenshot%202025-10-14%20001035.png?raw=1&v=2)

### 📈 Monthly Sales with Trend Line
![Trend Line](./images/Screenshot%202025-10-14%20001059.png?raw=1&v=2)

### 🔮 Monthly Sales Forecast (Next 6 Months)
![Monthly Revenue Trend](images/MONTHLY%20REVENUE%20TREND.png)


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
