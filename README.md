# 🛍️ Online Retail Sales Analysis  

## 📖 Project Overview  
This project analyzes the **Online Retail dataset (UCI Machine Learning Repository)**, which contains over 500,000 transactions from a UK-based online retailer between 2010–2011.  

The goal is to:  
- Explore sales trends  
- Understand customer behavior  
- Segment customers using RFM analysis  
- Build a simple sales forecast  

---

## ⚙️ Tech Stack  
- **Languages & Tools:** Python, Jupyter Notebook  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels  

---

## 📊 Analysis Workflow  

### 1. Data Cleaning & Preparation  
- Removed missing values, duplicates, and canceled/negative transactions  
- Created new features: `TotalPrice` (Quantity × UnitPrice), `InvoiceMonth`  
- Final dataset prepared for analysis and modeling  

### 2. Exploratory Data Analysis (EDA)  
- **Monthly Sales Trends:** Clear seasonality with peaks in Nov–Dec (holiday season)  
- **Top Customers:** A small number of customers contributed disproportionately to revenue (Pareto principle)  
- **Top Products:** Best-selling items (e.g., home décor, seasonal gifts) drive most sales, while many products had low demand  

### 3. Customer Behavior — RFM Analysis  
- Segmented customers into groups based on **Recency, Frequency, and Monetary** value  
- **Key segments:**  
  - **Champions:** Bought recently, spend the most, purchase frequently  
  - **Loyal Customers:** Buy often but spend less per order  
  - **At Risk:** Used to be active, but haven’t purchased recently  
  - **Hibernating / Lost:** Rarely purchase, low contribution  
- **Heatmap Insight:** Customers with high Recency & Frequency also show highest Monetary value (Champions)  

### 4. Forecasting / Prediction  
- Built a **Holt-Winters Exponential Smoothing model** on monthly sales  
- **Results:**  
  - Forecast captured strong **seasonality** (end-of-year peaks)  
  - Slight **upward trend** over time  
- **Business Value:** Helps in inventory planning, marketing timing, and budgeting  

---

## ✅ Business Insights  
1. **Seasonality:** Sales peak at year-end → plan stock, staff, and campaigns earlier  
2. **Top Customers Drive Revenue:** A small % of customers contribute most revenue → prioritize with loyalty programs  
3. **Customer Segmentation:** Focus on **Champions & Loyalists**, re-engage **At Risk** customers, automate campaigns for **Hibernating**  
4. **Product Strategy:** Keep bestsellers in stock, bundle low-demand items with popular ones  
5. **Forecasting:** Anticipate growth and align supply chain and marketing spend  

---

  
