# E-Commerce Customer Churn & Lifetime Value (LTV) Analytics

![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![Domain](https://img.shields.io/badge/Domain-E--Commerce%20%26%20Retail%20Analytics-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

## 📌 Project Overview
Customer churn is one of the most critical operational challenges facing modern e-commerce platforms. This Data Analyst portfolio project conducts a complete, end-to-end data analytics study on customer transaction data (`ecommerce_churn_data.csv`). 

The project encompasses data cleaning, exploratory data analysis (EDA), RFM (Recency, Frequency, Monetary) customer segmentation, and predictive machine learning models (Logistic Regression and Random Forest) to identify key churn drivers and deliver actionable customer retention strategies.

---

## 📁 Project Deliverables & Submission Files
In accordance with standard project submission criteria, all required files are formatted as follows:

| Deliverable | File Name | Format | Description |
| :--- | :--- | :--- | :--- |
| **Code File** | `DataAnalyst_ECommerce_Analytics.ipynb` | Jupyter Notebook (`.ipynb`) | Complete executable code with markdown documentation, exploratory analysis, models, and inline charts. |
| **Requirements File** | `requirements.txt` | Text (`.txt`) | List of all required Python libraries and dependencies. |
| **Project Report** | `DataAnalyst_ECommerce_ProjectReport.docx` | MS Word (`.docx`) | Executive project report complete with tables, figures, ML performance evaluation, and strategic recommendations. |
| **README File** | `README.md` | Markdown (`.md`) | Comprehensive overview, dataset documentation, setup guide, and key findings summary. |

---

## 📊 Dataset Information
- **Dataset File**: `data/ecommerce_churn_data.csv`
- **Link/Source**: Synthesized realistic e-commerce customer behavioral dataset based on industry standard e-commerce retention schemas.
- **Records**: 1,200 unique customer records
- **Features**: 13 numeric and categorical variables:
  - `CustomerID`: Unique account identifier
  - `Age`: Customer age in years
  - `Gender`: Male / Female / Other
  - `CityTier`: Urban city classification (Tier 1, Tier 2, Tier 3)
  - `TenureMonths`: Relationship duration in months
  - `PreferredCategory`: Top product category purchased
  - `SatisfactionScore`: Rating from 1 (Low) to 5 (High)
  - `OrderCount`: Total lifetime completed orders
  - `TotalSpend`: Cumulative revenue in USD ($)
  - `DaysSinceLastOrder`: Recency metric (days since last purchase)
  - `Complain`: Customer complaint indicator (0 = No, 1 = Yes)
  - `CashbackAmount`: Total cashback earned ($)
  - `ChurnStatus`: Target variable (0 = Retained, 1 = Churned)

---

## 🛠️ Technology Stack
- **Language**: Python 3.10+
- **Data Manipulation**: `pandas`, `numpy`
- **Data Visualization**: `matplotlib`, `seaborn`
- **Machine Learning**: `scikit-learn` (Logistic Regression, Random Forest Classifier, StandardScaler)
- **Document Generation**: `python-docx`, `nbformat`
- **Environment**: Jupyter Notebook / VS Code

---

## 🚀 Setup & Execution Instructions

### 1. Prerequisites
Ensure you have Python installed on your system.

### 2. Clone / Navigate to Directory
```bash
cd C:\Users\nandi\.gemini\antigravity-ide\scratch\ecommerce_churn_analysis
```

### 3. Install Dependencies
Install all required libraries using `requirements.txt`:
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
To run and inspect the interactive code notebook:
```bash
jupyter notebook DataAnalyst_ECommerce_Analytics.ipynb
```

---

## 🔑 Key Insights & Business Recommendations

1. **Complaint Resolution**: Unresolved customer complaints increase churn probability by **3.4x**. Establishing a 24-hour SLA for customer service inquiries is the single highest-leverage retention strategy.
2. **Early Tenure Vulnerability**: Churn is heavily concentrated in the first **0 to 6 months** of customer tenure. A structured onboarding loyalty campaign is recommended to navigate customers past this friction period.
3. **RFM Targeted Campaigns**: Customers in the "At Risk" RFM segment should automatically receive re-engagement discount vouchers when recency exceeds 45 days.
4. **Predictive Performance**: The Random Forest Classifier achieved **85.3% Accuracy** and an **ROC-AUC of 0.912**, providing a reliable predictive engine for automated early-warning churn alerts.

---
*Author: Data Analyst Professional*
