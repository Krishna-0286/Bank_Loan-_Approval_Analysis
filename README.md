# 🏦 Loan Approval Analysis Project

Welcome to the **Loan Approval Data Analysis** project! This repository provides a complete breakdown of how I collected, cleaned, explored, and visualized data related to loan applications to uncover business insights and build an interactive Power BI dashboard.

---

## 🔍 Project Overview

This project aims to analyze factors influencing loan approval decisions such as income, CIBIL score, education level, employment status, number of dependents, and various asset values.

* 📊 Dataset: Loan Approval Dataset (4269 rows, 13 columns)
* 📌 Objective: Understand which applicant features increase the chances of loan approval.

---

## 🛠️ Tools & Technologies Used

* **Python** (Pandas, NumPy) for data cleaning and manipulation
* **Matplotlib, Seaborn** for data visualization
* **Power BI** for dashboard creation
* **Kaggle** as the data source

---

## 📚 Dataset Info

Columns include:

* `loan_id`, `no_of_dependents`, `education`, `self_employed`, `income_annum`,
  `loan_amount`, `loan_term`, `cibil_score`, `residential_assets_value`,
  `commercial_assets_value`, `luxury_assets_value`, `bank_asset_value`, `loan_status`

---

## ⚙️ Data Cleaning Steps

* Removed leading/trailing whitespaces in column names
* Converted columns to appropriate datatypes
* Created new derived columns:

  * **Total Asset Value** = sum of all asset types
  * **Income-to-Loan Ratio**
* Verified missing values and handled them accordingly

---

## 📊 Key Visualizations & Dashboard Components

1. **Loan Approval Overview**
2. **Loan Status by Education & Employment**
3. **Income vs Loan Amount**
4. **CIBIL Score Distribution**
5. **Average Loan by Number of Dependents**
6. **Asset Distribution by Loan Status**
7. **KPI Cards**
 * Average loan amount, Average income, Total loan id, Average of cibil score

---

## 🧠 Insights & Conclusions

* Applicants with **CIBIL score > 700** had a higher chance of loan approval
* **Graduates** and **non-self-employed** individuals had better approval rates
* Positive correlation found between **annual income** and **loan amount requested**
* **Asset value** alone didn’t guarantee approval — **credit score was more impactful**

---

## 🎓 Skills Practiced

* Data Cleaning (renaming, datatype conversion, feature creation)
* Exploratory Data Analysis (EDA) with Python
* Data Visualization with Matplotlib & Seaborn
* Interactive Dashboarding in Power BI
* Business Insight Generation

---

## 📸 Dashboard Preview
To explore the dashboard, open the `.pbix` file in Power BI Desktop.
[link_of_Powerbi_dashboard]  (https://github.com/Krishna-0286/Bank_Loan-_Approval_Analysis/blob/main/BANK%20LOAN%20APPROVAL%20ANALYSIS.pbix)
Screen Shot of Dashboard
[Pic_of_dashboard](https://github.com/Krishna-0286/Bank_Loan-_Approval_Analysis/blob/main/BANK%20LOAN%20APPROVAL%20ANALYSS.png)


---

## 💼 Usage

To run the EDA notebook locally:

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook
```

To explore the dashboard, open the `.pbix` file in Power BI Desktop.

---

## 🏆 Author

**Krishna Kumar**
Aspiring Data Analyst | Skilled in Python, Pandas, Power BI, SQL
📫 [krishna-LinkedIn](https://www.linkedin.com/in/krishna-k-361225277/) | ✉️ [krishnakumar.email@example.com](krishnakumar995088.email@example.com)

---

## ✨ License

Free to use for learning and portfolio building. 

 
