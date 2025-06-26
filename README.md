
# 🏦 Banking Data Analysis and Dashboard Project

## 📌 Project Overview

This project provides a comprehensive analysis and visualization of customer banking data using:
- **Python (Pandas, Matplotlib, Seaborn)** for exploratory data analysis (EDA)
- **Power BI** for interactive dashboards

It is designed to help stakeholders understand customer behaviors, financial product usage, and demographic patterns that can drive data-driven decisions in the banking sector.

---

## 📁 Project Structure

```
📦 Banking-Data-Analysis/
│
├── 📊 Banking Dashboard(you).pbix       # Power BI Dashboard for visual insights
├── 📓 banking_EDA_colab.ipynb           # Jupyter Notebook for EDA
├── 📄 Bank_total_data.csv               # Main dataset
└── 📘 README.md                          # Project documentation (this file)
```

---

## 📊 Power BI Dashboard Highlights

- Customer age distribution
- Credit card usage by demographics
- Product holdings (loan, deposit, insurance)
- Relationship between job type and product subscription
- Regional differences in banking behavior

> **File**: `Banking Dashboard(you).pbix`

---

## 📈 Exploratory Data Analysis (Python)

Performed using `pandas`, `seaborn`, and `matplotlib`. Key steps include:

- Data cleaning: handling missing values and duplicates
- Univariate and bivariate analysis
- Correlation heatmaps
- Insights on:
  - Job-wise product usage
  - Age vs. balance trends
  - Marital status and product adoption

> **File**: `banking_EDA_colab.ipynb`

---

## 🧾 Dataset Description

> **File**: `Bank_total_data.csv`

Each row represents a customer with features like:

| Column Name        | Description                                  |
|--------------------|----------------------------------------------|
| `age`              | Age of the customer                          |
| `job`              | Type of occupation                           |
| `marital`          | Marital status                               |
| `education`        | Educational background                       |
| `default`          | Whether the customer has credit in default   |
| `balance`          | Account balance                              |
| `housing`          | Has a housing loan                           |
| `loan`             | Has a personal loan                          |
| `contact`          | Contact communication type                   |
| `pdays`, `previous`| Campaign-related indicators                  |
| `poutcome`         | Outcome of the previous marketing campaign   |

---

## 🚀 How to Run

### 1. Explore EDA

Open the `banking_EDA_colab.ipynb` in Google Colab or Jupyter:

```bash
pip install pandas matplotlib seaborn
```

Then run all cells to view insights.

### 2. View Dashboard

Open `Banking Dashboard(you).pbix` using Power BI Desktop (Windows only). You can interact with slicers and visuals for dynamic insights.

---

## 📌 Key Insights

- Customers aged 30–40 are most engaged in credit card and deposit services.
- Unmarried individuals are more likely to hold multiple financial products.
- Job type has a significant impact on loan uptake.
- Customers contacted via cellular are more responsive than those via telephone.

---

## 🤝 Contributions

Feel free to fork the repo, suggest improvements, or open issues!

---

## 📬 Contact

For queries, reach out to **Devisetty Leelakarthik** via GitHub or email.
