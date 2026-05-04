# 💳 Loan Default Risk Dashboard

## Project Overview

Loan defaults represent one of the most significant risks in the lending industry. This project analyzes **130,138 loan records** to identify key risk factors and patterns associated with loan default, visualized through an interactive Power BI dashboard.

The goal was to help lending institutions better understand which borrower profiles, loan types, and regional patterns are most associated with default risk — enabling smarter credit decisions and risk prioritization.

---

## 🛠️ Tools Used

- **Power BI Desktop** — Data modeling, DAX measures, and interactive dashboard
- **Microsoft Excel** — Data preparation and pivot analysis

---

## 📁 Dataset

| Property | Detail |
|---|---|
| Total Records | 130,138 loans |
| Total Features | 39 columns |
| Overall Default Rate | 24.55% |
| Year Covered | 2019 |

**Key columns include:**
- `loan_amount`, `Loan Band`, `rate_of_interest`, `term`
- `Credit_Score`, `Credit Band`, `Credit_Worthiness`
- `DTI Category`, `LTV`, `LTV Category`
- `income`, `Income Band`, `Gender`, `age`
- `loan_type`, `loan_purpose`, `Region`
- `Status` — target variable (1 = Default, 0 = No Default)

---

## 🔍 Key Findings

### 1. Overall Default Rate of 24.55%
Nearly 1 in 4 loans in the dataset resulted in default — representing **31,952 defaulted loans** out of 130,138 total, highlighting significant risk exposure across the portfolio.

### 2. Unknown DTI Borrowers Had the Highest Default Rate
Borrowers with unknown DTI (Debt-to-Income) data had a **67.49% default rate**, compared to Low DTI (27.66%), High DTI (19.18%), and Medium DTI (12.14%). This reveals that missing financial data is itself a strong risk signal.

### 3. High Income Borrowers Defaulted Most
Surprisingly, **high income borrowers had the highest default rate at 40%**, followed by Medium income (31.03%) and Low income (24.54%). This suggests income alone is not a reliable predictor of repayment behavior and must be combined with other factors.

### 4. Small Loans Defaulted More Than Large Loans
Counterintuitively, **small loans had the highest default rate at 37.02%**, compared to 26.10% for medium and 21.96% for large loans. This challenges the common assumption that larger loans carry more risk.

### 5. Credit Score Band Showed Minimal Differentiation
Both Fair and Good credit bands showed nearly identical default rates at approximately **24.55%**, suggesting that the credit scoring bands in this dataset may need refinement as a standalone risk predictor.

---

## 📊 Dashboard Highlights

The Power BI dashboard includes:
- **Default Rate by DTI Category** — visualizing how debt-to-income ratio affects default likelihood
- **Default Rate by Income Level** — comparing default rates across income bands
- **Default Rate by Credit Score Band** — showing how creditworthiness correlates with default risk
- **Default Rate by Loan Size** — revealing the counterintuitive relationship between loan size and default

---

## 💡 Business Recommendations

1. **Flag borrowers with missing DTI data** — A 67.49% default rate makes unknown DTI the strongest risk signal in the dataset
2. **Reassess income-based risk models** — High income alone does not predict repayment; it must be combined with DTI and loan size for accuracy
3. **Apply stricter screening to small loans** — Their higher default rate suggests current credit checks may be insufficient for this segment
4. **Refine credit score banding** — The near-identical default rates across credit bands suggest the current bands lack discriminatory power and need recalibration

---

## 📂 Project Structure

```
loan-default-risk-dashboard/
│
├── Book3.xlsx                        # Raw dataset
├── Loan_Default_Risk_Dashboard.pbix  # Power BI dashboard file
└── README.md                         # Project documentation
```

---

## 👤 Author

**Toluwanimi Awofisayo**
Mathematics Graduate | Data Analyst
📧 temijasopelincoln@gmail.com  
