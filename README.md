# 📊 Telecom Customer Churn Analysis

This project analyzes customer churn in a telecom dataset using **Python (EDA + ML)** and **Tableau (dashboards)**.  
The goal is to identify factors contributing to churn and visualize insights for business decisions.

---

## 🔹 Dataset
- Source: [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Rows: ~7,000 customers
- Features: Contract type, payment method, tenure, charges, services, churn status, etc.

---

## 🔹 Project Workflow
### 1. **Data Analysis & ML (Python)**
- Performed **EDA** (exploratory data analysis).
- Preprocessed categorical and numeric features.
- Trained **Random Forest Classifier** to predict churn.
- Used **SHAP values** for model explainability.


---

### 2. **Dashboard (Tableau)**
Created interactive visualizations in Tableau Public:
- **Pie Chart**: Overall churn distribution.  
- **Bar Chart**: Churn by contract type (Month-to-Month churn is highest).  
- **Box Plot**: Monthly charges distribution (churned customers usually pay higher).  

🔗 Tableau Dashboard Link: [View Here](https://public.tableau.com/app/profile/d.siva.kumar/viz/customerchurnanalysisproject_17573255496020/Dashboard1?publish=yes)

---

## 🔹 Insights
- Customers on **month-to-month contracts** churn much more than yearly contracts.  
- Higher **monthly charges** are linked to higher churn.  
- **Online security, tech support, and longer tenure** reduce churn.  



