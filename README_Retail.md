# 🛒 Real-world Data Project — Retail Sales Analysis

**Thiranex Skill Development & Future Tech — Project 4**

## 📌 Overview
This project performs an end-to-end data analysis on a real-world **Retail Sales dataset**. It covers data generation, business insight extraction, sales prediction using Linear Regression, and a comprehensive 9-chart visual dashboard.

---

## 🛠 Tech Stack
| Library | Purpose |
|---|---|
| `pandas` | Data manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Base plotting |
| `seaborn` | Statistical visualizations |
| `scikit-learn` | Sales prediction model |

---

## 📦 Dataset Features
| Column | Description |
|---|---|
| order_id | Unique order identifier |
| month | Month of sale |
| category | Product category |
| region | Sales region |
| payment_mode | Payment method used |
| quantity | Units sold |
| unit_price | Price per unit |
| discount_pct | Discount applied (%) |
| net_sales | Final sale amount |
| profit | Profit earned |
| rating | Customer rating (1–5) |

---

## 📊 Analysis Steps

### Step 1 — Dataset Overview
- Shape, types, missing value check

### Step 2 — Statistical Summary
- Descriptive stats for all numeric columns

### Step 3 — Key Business Insights
- Total revenue, profit, orders, avg order value
- Revenue breakdown by category, region, payment mode
- Peak sales month identification

### Step 4 — Sales Prediction
- Linear Regression to predict net sales
- R² Score and RMSE evaluation
- Feature coefficient analysis

---

## 📈 Visualizations (9-Chart Dashboard)

1. **Monthly Revenue Trend** — Line chart with area fill
2. **Revenue by Category** — Horizontal bar chart
3. **Revenue by Region** — Pie chart
4. **Profit by Category** — Bar chart
5. **Orders by Payment Mode** — Bar chart
6. **Discount vs Net Sales** — Scatter plot
7. **Customer Rating Distribution** — Histogram
8. **Actual vs Predicted Sales** — Regression scatter
9. **Top 5 High-Value Orders** — Horizontal bar

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/Pranav2006-HUB/retail-data-project.git
cd retail-data-project

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# 3. Run the script
python retail_project.py
```

**Outputs generated:**
- `outputs/retail_dashboard.png` — Full visual dashboard
- `outputs/retail_clean_data.csv` — Complete dataset
- `outputs/retail_summary.csv` — Category-wise summary

---

## 📂 Project Structure
```
retail-data-project/
│
├── retail_project.py           ← Main script
├── README.md                   ← This file
└── outputs/
    ├── retail_dashboard.png    ← Visual dashboard
    ├── retail_clean_data.csv   ← Full dataset
    └── retail_summary.csv      ← Summary report
```

---

## 🎯 Expected Outcome
- Apply data science skills in a real-world retail context
- Perform end-to-end data analysis and prediction
- Present findings with visualizations and conclusions

---

*Submitted for Thiranex Project 4 — Real-world Data Project (Retail)*
