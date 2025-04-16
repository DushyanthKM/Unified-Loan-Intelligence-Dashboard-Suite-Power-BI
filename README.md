# 💼 Bank Loan Report Dashboard | Case Study

---

## ❓ Problem Statement

Banks and financial institutions face a major challenge in identifying loan performance trends, assessing borrower risk, and optimizing their lending strategy in real time. This leads to delayed insights, higher default rates, and missed opportunities for profit.

---

## 🔍 Project Overview

This case study presents a comprehensive **Power BI dashboard solution** that transforms raw loan data into meaningful insights to guide lending decisions. The project covers everything from data cleaning, modeling, DAX-based KPIs to advanced visuals and storytelling.

> 🧠 Goal: Help stakeholders understand portfolio health, customer behavior, and regional risk factors to improve decision-making.

---

## 📊 Data Understanding

The dataset includes the following key attributes:

| Column Name        | Description                                        |
|--------------------|----------------------------------------------------|
| `loan_status`      | Status of loan (Fully Paid, Charged Off, etc.)    |
| `funded_amount`    | Amount sanctioned to the borrower                 |
| `amount_received`  | Amount repaid by the borrower                     |
| `interest_rate`    | Annual interest rate (%)                          |
| `dti`              | Debt-to-Income ratio                              |
| `purpose`          | Purpose of the loan (e.g., debt consolidation)    |
| `home_ownership`   | Borrower’s home ownership status (Rent, Mortgage) |
| `term`             | Duration of the loan (36 or 60 months)            |
| `grade` & `sub_grade` | Credit grade assigned to the borrower         |
| `state`            | Geographic location of the borrower               |
| `issue_date`       | Month the loan was issued                         |

---

## 🧭 Dashboard Structure

The Power BI Dashboard is divided into three interactive pages:

| Page | Focus Area              | Key Insights Generated |
|------|--------------------------|-------------------------|
| 1️⃣ Summary   | High-level KPIs & Overview   | Strategic portfolio health & growth trends |
| 2️⃣ Overview  | Segmented loan data by dimensions | Drill-down by state, loan grade, term, and status |
| 3️⃣ Details   | Loan-level granularity        | Customer behavior, interest rates, and repayment patterns |

---

## 🔢 Page 1 – Summary Dashboard Insights

### 🎯 KPI Metrics
- **Total Loan Applications:** `38.6K`  
- **Total Funded Amount:** `$435.8M`  
- **Total Amount Received:** `$473.1M`  
- **Average Interest Rate:** `12.05%`  
- **Average DTI (Debt to Income):** `13.33%`

✅ MoM Growth in All KPIs → Business scaling up successfully  
📈 Interest Rate & DTI rising slightly → Indicates higher-risk borrower segments being approved

---

### 🧠 Strategic Insights
- **Healthy ROI** as the amount received exceeds funded amount → Good loan structuring
- **Rising Applications (4.3K MTD)** → Increased customer trust and marketing success
- **Monitor Risk**: With rising DTI and interest rates, credit risk might increase

---

## 📍 Page 2 – Portfolio Segmentation Analysis

This page focuses on slicing the loan portfolio across key segments to identify trends.

### 🗺️ State-wise Analysis
- Top performing states by funded amount
- Certain states show lower repayment vs. funded → Need intervention strategy

### 🎓 Grade-wise Breakdown
- Grades **B & C dominate** the portfolio → Moderate risk, good volume
- **Grade A loans have lower interest but better repayment**

### ⏳ Loan Term Analysis
- Majority of loans issued with **36-month terms**
- 60-month loans are fewer but often tied to **higher amounts and interest**

📌 Strategy Tip: Offer customized loan terms based on risk-profile and past payment behavior.

### 🔴 Loan Status Tracker
- Mix of **Fully Paid**, **Current**, **Charged Off** loans
- Need more **predictive analytics** to preempt potential defaults

---

## 🔍 Page 3 – Individual Loan Detail Insights

This section provides a loan-by-loan view for micro-level decision making.

### 🏠 Home Ownership
- **RENT** is the most frequent ownership status → Indicates higher financial dependency
- **MORTGAGE** holders are secondary in count but often have larger loans

📌 Recommendation: Build customer personas focused on renters for financial literacy & planning tools.

---

### 💳 Loan Purpose
- Dominant reasons: **Debt Consolidation**, **Credit Card Refinancing**, **Home Improvement**
- High interest loans usually tagged to **debt** → Strong need for financial management tools

---

### 🎓 Grade and Sub-grade Trend
- Most borrowers lie in **Grade B & C**
- Subgrades like **B4, B5, C3** frequently appear
- Occasional **Grade D** loans → indicates acceptable risk tolerance

📌 Strategy: Launch incentive program for lower-grade customers with excellent payment behavior.

---

### 📈 Financial Observations
- **Funded Amounts** range: `$1,200 – $25,000`
- **Installments** vary from `$40 to $829/month`
- **Interest Rates**: `7.14% – 14.96%`

📌 Suggestion: Tiered EMI models + flexible repayment options can improve repayment and loyalty.

---

## 🧠 Final Business Recommendations

| Theme | Suggestion |
|-------|------------|
| 🎯 Targeting | Focus on renters, Grade B/C customers needing debt consolidation |
| 💸 Profitability | Optimize high-interest loans while reducing default risk |
| 🧪 Risk Management | Predict & control high-DTI and rising interest borrower profiles |
| 🔄 Loan Structuring | Promote 36-month low EMI options for affordability |
| 🤝 Customer Loyalty | Design loyalty benefits for consistent payers, especially in subgrades C3 & B5 |

