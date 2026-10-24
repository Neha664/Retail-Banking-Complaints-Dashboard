# 🏦 Retail Banking Complaints & Service Performance Dashboard

[![Dataset](https://img.shields.io/badge/Dataset-CFPB%20Open%20Data%20(2025)-E07A5F?style=for-the-badge)](https://www.consumerfinance.gov/data-research/consumer-complaints/)
[![Records](https://img.shields.io/badge/Audited%20Records-84%2C195-2D6A4F?style=for-the-badge)](https://github.com)
[![Tools](https://img.shields.io/badge/Tools-Excel%20%7C%20Pivot%20Tables%20%7C%20SLA%20Analytics-D97706?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://github.com)

An operational analysis and executive dashboard built from **84,195 CFPB retail banking records** across **472 U.S. financial institutions** to evaluate SLA response compliance, dispute resolutions, and friction root causes.

---

## 📊 Executive Dashboard Preview

<img width="1536" height="954" alt="Retail Banking Performance Dashboard" src="https://github.com/user-attachments/assets/5731a836-9740-4253-904a-22da606d0faf" />


---

## 🎯 Executive Scorecard (KPIs)

| Total Records | Timely Response Rate | Untimely Responses | Monetary Relief Rate |
| :---: | :---: | :---: | :---: |
| **84,195** | **99.28%** (83,586) | **609** | **10.58%** (8,907) |
| *100% Data Hygiene* | *Exceeds >98% Benchmark* | *Process Exceptions* | *Direct Restitution* |

---

## 🔍 Core Visual Analysis & Data Tables

### 1. Monthly Inflow & SLA Timeliness
* **Insight:** Inflow peaked in **January (18,249 disputes)** due to post-holiday transaction disputes, while SLA adherence remained above **99%** every month.

| Period | Total Inflow | Timely (Yes) | Untimely (No) | Monthly SLA |
| :--- | :---: | :---: | :---: | :---: |
| **Jan 2025 (Peak)** | **18,249** | 18,054 | 195 | 98.93% |
| **Feb – Dec Baseline (Avg)** | **~5,000–10,000** | — | — | **>99.3%** |
| **Full Year Total** | **84,195** | **83,586** | **609** | **99.28%** |

---

### 2. Top Institutions by Volume (Concentration)
* **Insight:** The **Top 3 institutions drive ~33%** of all disputes, led by large retail depositories and payment platforms.

| Rank | Institution | Complaints | Share | Primary Focus |
| :---: | :--- | :---: | :---: | :--- |
| **1** | **Navy Federal Credit Union** | 10,606 | 12.60% | Deposit holds & fund availability |
| **2** | **Wells Fargo & Company** | 8,937 | 10.61% | Account administration |
| **3** | **JPMorgan Chase & Co.** | 8,181 | 9.72% | Transaction processing |
| **4** | **Citigroup Inc.** | 7,912 | 9.40% | Billing & card charges |
| **5** | **U.S. Bancorp** | 6,680 | 7.93% | Checking account servicing |

---

### 3. Company Response Outcomes (Remediation)
* **Insight:** **84% of disputes closed with an explanation**, showing friction is driven primarily by policy and fee misunderstandings rather than bank errors.

| Outcome Category | Count | Share | Operational Action |
| :--- | :---: | :---: | :--- |
| **Closed with explanation** | **70,724** | **84%** | Written policy clarification |
| **Closed with monetary relief** | **8,907** | **11%** | Fee reversals / fund reimbursement |
| **Closed with non-monetary relief** | **4,210** | **5%** | Account unfreeze / credit update |
| **Untimely response** | **354** | **<1%** | SLA escalation breaches |

---

### 4. Primary Customer Issues (Root-Cause Pareto)
* **Insight:** Routine **"Managing an account" alone drives 53.4%** of all complaints; combined with overdraft fees, two processes drive **67.6% of all friction**.

| Rank | Primary Issue | Count | Share | Root Cause |
| :---: | :--- | :---: | :---: | :--- |
| **1** | **Managing an account** | **44,959** | **53.4%** | Deposit clearance holds & debit locks |
| **2** | **Problem caused by low funds** | **11,939** | **14.2%** | Overdraft & NSF penalty charges |
| **3** | **Closing an account** | **10,178** | **12.1%** | Closure delays & payout disbursement |
| **4** | **Lender/company charging account** | **9,609** | **11.4%** | Unauthorized recurring ACH debits |
| **5** | **Opening an account** | **6,957** | **8.3%** | Identity verification / KYC delays |

---

## 💡 Key Takeaways
1. **High Regulatory Adherence:** 99.28% SLA compliance across all 472 institutions.
2. **Dominant Root Cause:** 53.4% of friction stems from account access and deposit availability delays.
3. **Resolution Pattern:** 84% resolved with explanations, 11% received monetary remediation.

---

## 📁 Repository Structure
```text
├── README.md                                    <- Executive project summary
├── Retail_Banking_Performance_Dashboard.xlsx   <- Master Excel workbook & pivot model
└── dashboard_preview.png                        <- Dashboard screenshot
