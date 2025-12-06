# 📊 Banking Analysis Dashboard – Power BI

A comprehensive **Banking Analytics Dashboard** built using **Power BI**, designed to deliver actionable insights into client demographics, loan distribution, deposit performance, and overall financial health.

This dashboard is ideal for banking analysts, advisors, and managers who need a centralized, visually rich reporting solution.

---

## 📥 Dataset & Data Engineering

- The dataset was **downloaded from Kaggle**.
- Performed **basic feature engineering and preprocessing in Microsoft SQL Server (MSSQL)**.
- Cleaned, transformed, and structured the data using SQL queries.
- Imported the processed tables into **Power BI** for modeling and visualization.

---

## 🧭 Dashboard Pages

### **1. Loan Analysis**
✔ Total Loans: **4.38B**  
✔ Bank Loan: **1.77B**  
✔ Business Lending: **2.60B**  
✔ Credit Card Balance: **9.53M**

#### **Visuals**
- Loan by Income Band  
- Loan by Occupation  
- Loan by Branch (BRId)  
- Loan by Nationality  
- Joining Year Trend  
- Gender Distribution  

📷 **Screenshot:**  
![Loan Analysis](https://drive.google.com/uc?id=1CARXgXqriZjqLrmMkuZ6Ez2fg89cZagq)

---

### **2. Deposit Analysis**
✔ Total Deposits: **3.77B**  
✔ Checking Account Amount: **963.28M**  
✔ Saving Account Amount: **698.73M**  
✔ Bank Deposit: **2.01B**

#### **Visuals**
- Deposits by Income Band  
- Deposits by Occupation  
- Deposits by Branch  
- Deposits by Nationality  
- Joining Year Trend  
- Customer Gender Ratio  

📷 **Screenshot:**  
![Deposit Analysis](https://drive.google.com/uc?id=1RzAMnlmJve535Fvuckr4N6SM2XG26xFu)

---

### **3. Summary Dashboard**
High-level combined overview of all banking metrics.

#### **Key Metrics**
- Total Clients: **3000**
- Business Lending: **2.60B**
- Foreign Currency Amount: **89.65M**
- Total SuperAnnual: **76.59M**
- Total CC Amount: **9.53M**
- Properties Owned: **4556**

📷 **Screenshot:**  
![Summary Dashboard](https://drive.google.com/uc?id=1JeKlS5HAHMtHiolinQrDKqEybp-YrEnB)

---

### **4. Additional Page (Optional)**
If you have a 4th page, add its description here.

📷 **Screenshot:**  
![Extra Page](https://drive.google.com/uc?id=1zUOaGgc0H6bQdv7xoC36BPReNPrXRVRy)

---

## 🛠 Tech Stack

| Component | Technology |
|----------|------------|
| Data Source | Kaggle Dataset |
| Data Cleaning | MSSQL (Feature Engineering, Joins, Aggregations) |
| BI Tool | Power BI Desktop |
| Data Modeling | DAX, Power Query |
| Export | PDF + PNG Screenshots |

---

## 🔑 Key Insights

- Medium-income customers contribute **50%+** of both loan and deposit volume.
- Significant business lending activity (**2.60B**).
- Checking account balances exceed saving accounts.
- Strong customer acquisition trend from **2018–2021**.
- Diverse nationality distribution reflecting a broad customer base.

---

## ▶️ How to Use

1. Download the `.pbix` file (if included).
2. Open it in **Power BI Desktop**.
3. Refresh the MSSQL or CSV/Kaggle connections.
4. Interact with slicers & filters:
   - Income Band  
   - Branch  
   - Gender  
   - Occupation  
   - Nationality  
   - Advisor  

---

## 🔮 Future Improvements
- Add forecasting for deposits/loans using DAX or ML models  
- Integrate customer churn prediction  
- Include branch-level drill-through views  
- Add anomaly detection for loan defaults  

---

## 🏁 Conclusion

This dashboard delivers a clear, insightful visualization of core banking operations.  
With SQL-based feature engineering and Power BI visual analytics, it offers a powerful tool for understanding customer behavior, financial product usage, and organizational performance.

---

## ⭐ If you like this project, feel free to star the repository!
