# HR Employee Attrition Analysis
### Uncovering what drives employees to leave — and what keeps them

![Python](https://img.shields.io/badge/Python-3.12-blue)
![pandas](https://img.shields.io/badge/pandas-2.2.2-green)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange)

---

## Project Overview

This project analyzes the IBM HR Analytics Employee Attrition dataset to identify
the key factors that drive employee turnover. Using Python for data cleaning and
analysis, SQL for querying, and visualizations to communicate findings, the goal
is to produce actionable insights an HR team could realistically use to reduce
attrition.

---

## Business Questions

1. What is the overall attrition rate, and which departments lose the most people?
2. Does income, job level, or overtime predict who leaves?
3. Which age group and tenure band carries the highest attrition risk?
4. Does work-life balance or job satisfaction correlate with staying or leaving?
5. What does the profile of a "flight risk" employee look like?

---

## Dataset

- **Source:** [IBM HR Analytics Employee Attrition & Performance — Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Size:** 1,470 employees × 35 features
- **Type:** Structured, tabular — no missing values

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python 3.12 | Core analysis language |
| pandas | Data cleaning and manipulation |
| matplotlib & seaborn | Data visualisation |
| SQLite (sqlite3) | SQL querying within Python |
| Jupyter Notebook | Interactive analysis environment |
| Power BI | Final interactive dashboard |
| GitHub | Version control and portfolio |

---

## Key Findings

### Overall
- Company attrition rate: **16.1%** — 237 out of 1,470 employees left

### Q1 — Attrition by Department
- Sales has the highest attrition rate, exceeding the company average
- Human Resources has the lowest attrition rate

### Q2 — Overtime, Income & Job Level
- Overtime workers leave at **30.5%** vs only **10.4%** for non-overtime — 3× higher
- Employees who left earned a median of **$3,202/month** vs **$5,204** for those who stayed — 38% less
- Junior employees (Job Level 1) have the highest attrition rate

### Q3 — Age & Tenure
- Employees aged **18–25** have the highest attrition rate of any age group
- Employees in their **first 2 years** leave at **29.8%** — nearly 1 in 3
- Attrition drops significantly after year 2, confirming the first 2 years as the critical retention window

### Q4 — Satisfaction & Work-Life Balance
- Low job satisfaction employees leave at roughly **double** the rate of Very High satisfaction employees
- Poor work-life balance consistently correlates with higher attrition across all levels

### Q5 — Flight Risk Profile
- **29 employees (2% of workforce)** meet all flight risk criteria
- Their attrition rate is **58.6%** — 3.6× the company average
- Profile: junior, overtime, 0–2 years tenure, low satisfaction, income ~$2,690/month
- 82.8% are in Research & Development (Research Scientists & Lab Technicians)

---

## Recommendations

| Priority | Action | Based On |
|---|---|---|
| 🔴 High | Review overtime policy for junior employees | Q2 — strongest predictor |
| 🔴 High | Immediate retention focus on 29 flight risk employees | Q5 — 58.6% attrition rate |
| 🟡 Medium | Strengthen onboarding for first 2 years | Q3 — 29.8% early attrition |
| 🟡 Medium | Review compensation for Level 1 roles | Q2 — 38% income gap |
| 🟢 Ongoing | Monitor satisfaction scores in Sales | Q1 + Q
---

## How to Run

```bash
git clone https://github.com/Fatimah-AlRadwan/hr-attrition-analysis.git
cd hr-attrition-analysis
pip install pandas matplotlib seaborn jupyter
jupyter notebook
```

---

## Author

**Fatimah Alradwan** — MIS Graduate, Imam Abdulrahman Bin Faisal University  
📍 Eastern Province, Saudi Arabia  
[LinkedIn](https://linkedin.com/in/fatimah-alradwan) · [GitHub](https://github.com/Fatimah-AlRadwan)

---
