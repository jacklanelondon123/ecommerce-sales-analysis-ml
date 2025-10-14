# 🛍️ E-commerce Sales Analysis & Machine Learning Project

This end-to-end project explores online retail sales data to uncover business insights, apply machine learning models, forecast future sales, and segment customers using RFM analysis.  
It demonstrates a complete data science workflow — from **data exploration** and **cleaning**, to **predictive modeling** and **visual storytelling**.

---

## 📊 1. Project Overview

**Dataset:** Online Retail II  
**Objective:** Analyze customer behavior, predict high-value customers, forecast sales, and segment audiences for marketing optimization.

---

## 🧹 2. Data Exploration & Cleaning

The data was loaded and cleaned in Python to remove null values, duplicates, and non-numeric Customer IDs.

### Key Cleaning Steps:
- Removed missing CustomerID records  
- Calculated `Sales = Quantity × UnitPrice`  
- Converted InvoiceDate to datetime format  
- Filtered out negative transactions (returns)

![Data Summary](images/Screenshot%202025-10-14%20000401.png)
![Sample Cleaned Data](images/Screenshot%202025-10-14%20000620.png)

---

## 📈 3. Exploratory Analysis

Explored top-selling countries and products.

![Top Countries](images/Screenshot%202025-10-14%20000912.png)
![Top Products](images/Screenshot%202025-10-14%20000931.png)

---

## 🤖 4. Machine Learning Models

### 4.1 Logistic Regression – High-Value Customer Prediction

Created a target variable (`HighValue`) using median sales as threshold.  
Model achieved **100% accuracy** due to clear separation in customer purchasing patterns.

![Logistic Regression Results](images/Screenshot%202025-10-14%20011559.png)

### 4.2 Random Forest – Feature Importance

The Random Forest model confirmed that **TotalSales** was the dominant predictor of customer value.

![Random Forest Results](images/Screenshot%202025-10-14%20011624.png)
![Feature Importance](images/Screenshot%202025-10-14%20011654.png)

---

## 🧩 5. Customer Clustering (K-Means)

Performed K-Means clustering using Recency, Frequency, and Monetary values to identify key customer segments.

![Elbow Method](images/Screenshot%202025-10-14%20011941.png)
![Customer Segments](images/Screenshot%202025-10-14%20012029.png)

**Cluster Insights:**
| Cluster | Description | Behavior Summary |
|----------|--------------|------------------|
| 0 | Average Buyers | Moderate spenders |
| 1 | Low-Value | Infrequent buyers |
| 2 | Top Buyers | Extremely high volume |
| 3 | Engaged Loyalists | Frequent and recent purchases |

---

## ⏳ 6. Time Series Forecasting (ARIMA)

Forecasted future monthly sales using ARIMA model.

![Monthly Sales Trend](images/Screenshot%202025-10-14%20012225.png)
![Forecasted Sales Output](images/Screenshot%202025-10-14%20012319.png)
![Sales Forecast Chart](images/Screenshot%202025-10-14%20012226.png)

**Insight:** Future sales are predicted to stabilize around **£650,000/month**.

---

## 💎 7. RFM Customer Segmentation

Used **Recency, Frequency, and Monetary** scores to group customers into meaningful business segments.

![RFM Table](images/Screenshot%202025-10-14%20012836.png)
![Segment Summary](images/Screenshot%202025-10-14%20013902.png)
![Segment Chart](images/Screenshot%202025-10-14%20013923.png)

**Segment Summary:**
| Segment | Customers | Avg Spend (£) |
|----------|------------|----------------|
| Champions | 1207 | 5477 |
| Loyal Customers | 1075 | 1308 |
| Potential Loyalist | 1109 | 544 |
| At Risk | 719 | 255 |
| Lost | 202 | 143 |

---

## 💡 8. Key Insights

- **Top buyers (Cluster 2)** contribute the majority of revenue.  
- **Customer loyalty programs** could focus on converting “Potential Loyalists” into “Champions.”  
- **Sales are seasonal**, with peaks during Q4 months.  
- **Forecast suggests steady growth** over the next 6 months.  
- **RFM analysis** highlights strong retention potential.

---

## ⚙️ 9. How to Run This Project

### 🧩 Prerequisites
- Python 3.10+  
- Jupyter Notebook or VSCode  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `statsmodels`

### ▶️ Steps
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/ecommerce-sales-analysis-python.git
   cd ecommerce-sales-analysis-python
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebook:  
   ```bash
   jupyter notebook Ecommerce_Sales_Analysis.ipynb
   ```

---

## 🧰 10. Technologies Used

- **Python (Pandas, Numpy, Matplotlib, Seaborn, Sklearn, Statsmodels)**  
- **Jupyter Notebook**  
- **GitHub** for version control and project presentation  

---

### ✨ Author  
**JacklaneLondon123**  
📧 *Data Analyst | Portfolio Project (Python + ML + Business Insights)*  
🌐 GitHub: [github.com/jacklanelondon123](https://github.com/jacklanelondon123)

---
