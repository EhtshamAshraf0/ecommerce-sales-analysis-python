# 🛍️ E-Commerce Sales Analysis using Python

## 📘 Project Overview
This project focuses on analyzing an e-commerce company's sales data to uncover key insights related to **revenue growth**, **customer behavior**, and **product performance**.  
Using Python for data cleaning, exploration, and visualization, the goal is to help the business make **data-driven decisions** to improve profitability and efficiency.

---

## 🧰 Tools & Libraries Used
- **Python**
- **pandas** – data cleaning and manipulation  
- **numpy** – numerical operations  
- **matplotlib & seaborn** – data visualization  
- **Jupyter Notebook** – interactive analysis environment

## Data Files Link : https://drive.google.com/drive/folders/1HZj6CWby9nLMV1s8gglaYp1cymoXDXIV?usp=drive_link

## 📁 Project Structure
```
Ecommerce-Sales-Analysis/
│
├── data/
│   ├── LINK : https://drive.google.com/drive/folders/1HZj6CWby9nLMV1s8gglaYp1cymoXDXIV?usp=drive_link
│   
│
├── notebooks/
│   └── sales_analysis.ipynb
│
├── visuals/
│   ├── Monthly_Revenue.png
│   ├── Monthly_Revenue_Normal_Vs_Outliers.png
│   ├── Top_products_By_Revenue.png
│   ├── Top_products_By_Quantity.png
│   ├── Top_Customers_By_Revenue.png
│   ├── Return_Rate_By_Month.png
│   ├── RFM.png
│   └── Metric_All_vs_Normal.png
│
└── README.md
```
## 🧹 Data Cleaning & Preparation
- Removed duplicate and missing values  
- Standardized column names and data types  
- Converted `InvoiceDate` to datetime format  
- Created new calculated fields such as:
  - `Revenue = Quantity × Unit Price`
  - `Month` and `Year` extracted from `InvoiceDate`
- Filtered invalid transactions and normalized product/category names  

---

## 📊 Exploratory Data Analysis (EDA)
The analysis explored key business questions, including:
1. Who are the **top customers** by revenue?  
2. Which **products** generate the highest sales?  
3. What are the **monthly and yearly sales trends**?  
4. What’s the **return rate and refund pattern**?  
5. How can **customer behavior** guide business decisions?  

---

## 💡 Key Insights
- 🏆 **Top 10 Products** contributed nearly **10% of total revenue**  
- 👤 **Top 10 Customers** contributed nearly **14% of total revenue**  
- 📅 Sales **peak between November and December**, showing strong holiday season demand  
- 💰 **Return Rate** fluctuates **month-over-month**, highlighting product return issues that may need process optimization  

---

## 📈 Visualizations
Key visualizations generated using Matplotlib and Seaborn:
- **Monthly Revenue Trend**
- **Monthly Revenue Trend (Normal vs. Outliers)**
- **Top Products by Revenue & Quantity**
- **Top Customers by Revenue**
- **Return Rate by Month**
- **Metrics: All vs. Normal Comparison**

📁 *Visuals are included in the “visuals” folder.*
```
visuals/
├── Monthly_Revenue.png
├── Monthly_Revenue_Normal_Vs_Outliers.png
├── Top_products_By_Revenue.png
├── Top_products_By_Quantity.png
├── Top_Customers_By_Revenue.png
├── Return_Rate_By_Month.png
├── RFM.png
└── Metric_All_vs_Normal.png
```

🚀 How to Run This Project

**Clone the repository:**
git clone https://github.com/EhtshamAshraf0/ecommerce-sales-analysis-python.git

**Open the notebook:**
jupyter notebook notebooks/sales_analysis.ipynb

**Install required libraries:**
pip install pandas numpy matplotlib seaborn

Run all cells to reproduce the analysis and visualizations.

🧠 Key Learnings

**Performed end-to-end data analysis in Python.**
**Improved understanding of sales KPIs and customer behavior.**
**Strengthened data visualization and storytelling skills using Matplotlib & Seaborn.**
**Learned to translate business questions into actionable insights.**

✍️ Author

Ehtsham Ashraf
📊 Data Analyst | Python | Excel | Power BI

### 🔗 LinkedIn : https://www.linkedin.com/in/ehtsham-ashraf-61b1b8342/
### 🔗💻 GitHub : https://github.com/EhtshamAshraf0
