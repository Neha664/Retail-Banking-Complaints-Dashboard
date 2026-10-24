# 🏦 Retail Banking Complaints & SLA Performance Dashboard

[![Dataset](https://img.shields.io/badge/Dataset-CFPB%20Open%20Data-blue.svg)](https://www.consumerfinance.gov/data-research/consumer-complaints/)
[![Tools](https://img.shields.io/badge/Tools-Advanced%20Excel%20%7C%20Pivot%20Tables%20%7C%20SLA%20Analytics-green.svg)]()
[![Status](https://img.shields.io/badge/Data%20Audit-100%25%20Verified-brightgreen.svg)]()

An end-to-end operational analytics and business intelligence project analyzing **84,195 consumer retail banking complaints** across **472 financial institutions** sourced from the Consumer Financial Protection Bureau (CFPB). 

This project audits raw record hygiene, tracks institutional SLA compliance against statutory deadlines, identifies root causes of friction in retail banking workflows, and evaluates remediation outcomes across traditional commercial banks, credit unions, and fintech platforms.

---

## 📊 Executive Dashboard Preview

![Executive Dashboard Preview](dashboard_preview.png)

> *The interactive workbook includes dynamic KPI cards, high-contrast Pivot Charts, and synchronized slicers for multi-dimensional operational filtering.*

---

## 🎯 Key Performance Indicators (KPIs)

| Metric | Measured Value | Operational Context & Benchmark |
| :--- | :--- | :--- |
| **Audited Records** | **84,195** | 100% data integrity verified; 0 missing Complaint IDs across 472 distinct entities. |
| **Timely Response Rate (SLA)** | **99.28%** | 83,586 on-time responses; easily exceeds the statutory 98% industry SLA requirement. |
| **Monetary Relief Rate** | **10.58%** | 8,907 customer cases resolved with direct financial restitution (refunds, fee reversals). |
| **Primary Root Cause** | **53.4%** | 44,959 complaints concentrated in routine account management (deposit holds & card debits). |

---

## 🔍 Core Business Insights & Operational Findings

### 1. High Regulatory SLA Adherence with Seasonal Surge
* Across all 472 institutions, **99.28%** of consumer disputes were acknowledged and closed within regulatory response deadlines.
* Operational volume spiked sharply in **January (18,249 complaints)** driven by holiday transaction reconciliation, post-holiday billing reviews, and account adjustments before normalizing to a baseline of ~5,000–6,500 monthly inquiries.

### 2. Root-Cause Concentration (Pareto Principle)
* Over half of all customer grievances (**53.4% / 44,959 records**) originated from routine **Account Management** friction points—predominantly check deposit clearance delays, fund availability holds, and debit card authorization locks.
* Unanticipated **Overdraft & Service Fees** comprised the second-largest driver at **14.2% (11,939 records)**. Together, these two operational areas account for over **67% of all customer dissatisfaction**.

### 3. Remediation Policy Disparities Across Banking Models
* **Traditional Commercial Banks:** Exhibited structured dispute settlement mechanisms with high financial restitution rates (e.g., Bank of America settled ~36% of grievances with direct monetary relief).
* **Fintechs & Neobanks:** Resolved fewer than 1% of disputes with financial relief, relying overwhelmingly on written administrative explanations, revealing substantial policy differences across modern retail banking models.

---

## 🛠️ Data Audit & Methodology

1. **Hygiene & Validation Audit:**  
   Cleaned 84,195 raw transaction records; validated primary key integrity, standardized date formats, and verified zero unrecorded or corrupted identifiers.
2. **Data Modeling & Pivot Aggregations:**  
   Structured normalized calculation layers for monthly inflow velocity, institutional response timeliness, grievance hierarchies, and relief distribution.
3. **Executive Dashboard Engineering:**  
   Constructed high-visibility executive KPI summary blocks, formatted charts with consistent data scales, and connected slicers for real-time operational drill-downs.

---

## 📂 Repository Structure

```text
├── README.md                                     <- Project documentation & business executive summary
├── Retail_Banking_Executive_Dashboard.xlsx      <- Master workbook with data model, pivot layer & dashboard
└── dashboard_preview.png                         <- High-resolution dashboard screenshot
