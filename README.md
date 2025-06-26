# 🏦 Risk Analysis for Bank

This project analyzes customer credit risk for a bank using Python and Power BI. It includes cleaning data, exploring trends, building a basic risk model, and visualizing insights in an interactive dashboard.

---

## 📁 Files in this repo

| File | Description |
|------|-------------|
| `Bank_total_data.csv` / `.xlsx` | Original dataset |
| `banking_EDA_colab.ipynb` | Python notebook with data cleaning and analysis |
| `Banking Dashboard New.pbix` | Final Power BI dashboard |
| `bank Analysis Dashboard(OLD).pbix` | Previous version of dashboard |

---

## ✅ Goals

1. Find patterns in customer risk levels
2. Identify key factors that lead to default
3. Show results using clear visuals and filters

---

## 📊 Data Overview

| Column | Description |
|--------|-------------|
| Customer_ID | Unique ID per person |
| Age | Customer age |
| Income | Annual income |
| Loan_Amount | Current loan balance |
| Credit_Score | Credit score (300–850) |
| Default_Flag | 1 = defaulted, 0 = good customer |

More details are available in the notebook.

---

## 🔍 Steps Followed

1. Cleaned and formatted the data
2. Created new columns like debt-to-income ratio
3. Used simple machine learning to group risk levels
4. Built a Power BI report to explore the findings

---

## 🚀 How to Use

1. Clone the repo:
```bash
git clone https://github.com/LeelaKarthik-26/Risk-Analysis-for-bank
```
2. Open the notebook `banking_EDA_colab.ipynb` in Google Colab or Jupyter
3. Run all cells to see the analysis
4. Open the `.pbix` file in Power BI Desktop to view the dashboard

---

## 🧰 Tools Used

- Python (pandas, matplotlib, seaborn, scikit-learn, xgboost)
- Google Colab
- Power BI Desktop

---

## 📌 Results (Summary)

- The model can predict risk fairly well (AUC ~ 0.87)
- Around 11% of customers are high risk
- Main factors: Credit Score, Income, Loan Amount, Tenure

---

## 🤝 Feedback & Contributions

Feel free to open issues or pull requests with ideas or improvements!

---

*Made by Leela Karthik*
