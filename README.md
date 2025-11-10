# 🏥 Healthcare Claims Dashboard

An interactive **Tableau dashboard** analyzing synthetic healthcare claim data to visualize trends in claim outcomes, payment performance, payer mix, and top rejection reasons.  
Data cleaning and preprocessing were performed using **Python**.

---

## 📊 Dashboard Preview
![Healthcare Claims Dashboard](images/dashboard_preview.png)

---

## ⚙️ Tools & Technologies
- **Python (Pandas, NumPy)** – data cleaning and preprocessing  
- **Tableau Desktop / Tableau Public** – dashboard design and visualization  
- **Jupyter Notebook** – exploratory data analysis  
- **Kaggle Dataset** – synthetic healthcare claim dataset (no real patient data)

---

## 🧹 Data Preparation in Python

Key cleaning and transformation steps included:
- Removed duplicates and standardized column names  
- Handled missing and invalid claim values  
- Computed **Paid %**, **Denial Rate**, and **Claim Duration** metrics  
- Mapped insurance and outcome categories for Tableau analysis  

## 📈 Key Insights

- Overall Paid Rate: 68% of total claims were paid

- Denial Rate: 66.6%

- Top Payers: Medicaid and Commercial plans

- Top Rejection Reasons: Missing authorization and incorrect billing info

- Top 5 Physicians: Maintained 88%+ paid claim success rate

## 🖥️ Tableau Dashboard Highlights

- KPI Summary Cards: Total Claims, Paid %, Denial Rate

- Donut Chart: Outcome Distribution (Paid, Partially Paid, Denied)

- Line Charts: Claims Trend & Accounts Receivable Trend

- Bar Charts: Top Payers, Top Rejection Reasons, Physician Performance

- Interactive Filters by Insurance Type and Claim Status

## 📚 Dataset

- Synthetic healthcare claim dataset from Kaggle (for training and demonstration purposes only).

- Note: This dataset contains no real patient information.
