# 🛒 E-Commerce Customer Churn & Retention Analysis

## 📌 Problem Statement
High customer attrition erodes retail profitability due to significant Customer Acquisition Costs (CAC). Across **5,630 customer profiles**, the platform experiences an **18.61% baseline churn rate** (1,048 lost accounts). This project identifies the key behavioral, transactional, and logistical triggers driving customer drop-off and provides actionable retention strategies.

## 🛠️ Tools Used
* **Python (Pandas, NumPy, Matplotlib, Seaborn):** Data cleaning, median imputation, and Exploratory Data Analysis (EDA) in Jupyter Notebook.
* **Microsoft Power BI & DAX:** Automated Power Query ETL pipeline, centralized `_Measures` calculation engine, and a two-page interactive dashboard.
* **GitHub & Google Drive:** Cloud version control, portfolio hosting, and public file sharing.

## 📊 Interactive Dashboard Link
* **Access the Power BI Dashboard (`.pbix`):** [View / Download Interactive Dashboard on Google Drive](https://google.com)

## 🔍 Key Findings
* **Onboarding Vulnerability Window:** Customer attrition spikes to **78.05%** during **Months 0 and 1**. Once shoppers survive past Month 2, retention stabilizes across the customer lifecycle.
* **Payment Channel Friction:** Manual checkout methods experience the highest attrition—led by **UPI (20.54%)** and **E-Wallets (19.39%)**—compared to **Cash on Delivery (13.57%)**.
* **Service Resolution Multiplier:** Customers who log a formal complaint churn at a **26.8% rate** compared to **15.9%** for users without complaints (nearly a **70% higher relative risk**).
* **Logistical Distance Strain:** Shipping distances beyond the **14 km median** correlate with lower satisfaction scores and higher support ticket volume in Tier 2 and Tier 3 cities.

## 🚀 Business Recommendations
1. **First-30-Day Activation Habit Loops:** Trigger automated tiered discount vouchers on Days 5, 12, and 19 post-registration to encourage repeat orders before the 30-day drop-off window closes.
2. **Auto-Pay Migration Campaign:** Offer a one-time wallet credit or cashback incentive to migrate UPI and E-Wallet users toward saved card or auto-debit billing.
3. **12-Hour Priority Support Triage:** Route complaints logged by new users (`Tenure <= 3` months) to a rapid-response support queue with a 12-hour resolution SLA.
4. **Regional 3PL Micro-Fulfillment Hubs:** Partner with local third-party logistics hubs in high-volume Tier 2 and Tier 3 cities to reduce delivery distances beyond 14 km.

## 📁 Repository Structure
* `churn_analysis.ipynb` — Complete Python EDA and data preparation notebook.
* `Customer_Churn_Dashboard.pbix` — Interactive two-page Power BI dashboard file.
* `ECOMMERCE CHURN CAPSTONE.pdf` — Full written capstone report with visual insights and recommendations.
* `ecommerce_customer_churn.xls` — E-commerce customer churn dataset.
