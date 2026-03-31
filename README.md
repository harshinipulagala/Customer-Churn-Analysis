## 📊 Customer Churn Analysis Dashboard

🚀 **Project Overview** 

Customer churn is a critical business problem that directly impacts revenue and growth. This project focuses on analyzing customer behavior to identify patterns behind churn and provide actionable insights to improve retention.

The solution combines SQL Server (ETL) and Power BI (Visualization) to transform raw data into meaningful business intelligence.

---

**🎯 Objectives**

* Analyze customer churn behavior across multiple dimensions
* Identify key factors contributing to churn
* Segment customers based on demographics, services, and account details
* Build an interactive dashboard for business decision-making
* Enable future churn prediction strategies

---

**🛠️ Tech Stack**

* **Database:** Microsoft SQL Server
* **ETL Tool:** SQL (SSMS)
* **Visualization:** Power BI
* **Data Source:** Telecom Customer Dataset

---
**📂 Data Pipeline Architecture**

1. **Data Ingestion**

   * Imported raw CSV data into SQL Server staging table

2. **Data Cleaning & Transformation**

   * Handled null values
   * Standardized categorical fields
   * Created production-ready dataset

3. **Data Modeling**

   * Created views:

     * `vw_ChurnData` → Churned & Stayed customers
     * `vw_JoinData` → Newly joined customers

4. **Power BI Transformation**

   * Created calculated columns:
     * Churn Status
     * Age Groups
     * Tenure Groups

---

 **📊 Key Metrics**

* Total Customers
* Total Churn
* Churn Rate (%)
* New Joiners

---

**📈 Dashboard Insights**

The dashboard provides insights across:

**👥 Demographics**

* Churn rate by gender
* Customer distribution by age group

**💳 Account Information**

* Churn rate by payment method
* Contract-based churn analysis
* Tenure group analysis

**🌍 Geographic Analysis**

* Top states with highest churn

**📉 Churn Distribution**

* Churn categories (Competition, Price, etc.)
* Detailed churn reasons

**📡 Services Analysis**

* Internet type vs churn rate
* Service usage impact on churn

---

**⚙️ SQL Implementation Highlights**

* Created database: `db_Churn`
* Staging table for raw data
* Null handling using `ISNULL()`
* Data transformation into production table
* View creation for reporting

**🎨 Dashboard Features**

* Interactive filters (Monthly Charge, Marital Status)
* KPI cards for quick insights
* Drill-down capabilities
* Clean and professional UI design

---

**📌 Key Business Insights**

* Customers with shorter tenure have higher churn rates
* Month-to-month contracts show maximum churn
* Certain states contribute disproportionately to churn
* Customers without additional services are more likely to churn

---

**📷 Dashboard Preview**
<img width="1440" height="808" alt="image" src="https://github.com/user-attachments/assets/2c9f9c89-fd14-4636-9859-0b5c70c2eb88" />


---

**🎯 Business Impact**

* Helps companies reduce churn
* Improves customer retention strategies
* Enables data-driven decision making

---

**🔮 Future Enhancements**

* Machine Learning model for churn prediction
* Real-time data integration
* Advanced customer segmentation

---

**👤 Author**

**Harshini Pulagala**
---

**⭐ If you like this project**

Give it a ⭐ on GitHub and share your feedback!
