# CIB Banking Analytics & Power BI Dashboard

An end-to-end banking analytics project analyzing 5,000 customers, 20,000 transactions, loan portfolios, card usage, and support ticket performance.

---

## 📌 Project Overview
This repository contains a comprehensive banking dataset and an interactive Power BI dashboard designed to provide actionable financial and operational insights for Commercial International Bank (CIB).

- **Dataset:** `CIB_Banking_Analytics_Dataset.xlsx`
- **Dashboard:** `finalprojectamit.pbix`

---

## 📊 Key Insights & Metrics

* **Account Portfolio Balance:** EGP 249.37M total deposits across 5,000 accounts (Average balance: EGP 49,874).
* **Transaction Volume:** EGP 100.11M processed across 20,000 transactions (Payments, Transfers, Deposits, and Withdrawals).
* **Loan Book Portfolio:** EGP 616.66M extended across 2,500 active loans (Average interest rate: 7.48%).
* **Cards Issued:** 4,000 active cards (Debit, Credit, and Prepaid).
* **Support Ticket Resolution:** 3,000 recorded calls with a **49.3% resolution rate** (50.7% open disputes and access issues).

---

## 🗂️ Data Architecture

The data model connects 6 transactional and demographic tables via a Star/Snowflake Schema:

1. **Customers:** 5,000 profiles (`CustomerID`, `JoinDate`, Demographics)
2. **Accounts:** 5,000 accounts (`AccountType`, `Balance`, `CreatedDate`)
3. **Transactions:** 20,000 log entries (`TransactionType`, `Amount`, `TransactionDate`)
4. **Loans:** 2,500 loan records (`LoanType`, `LoanAmount`, `InterestRate`)
5. **Cards:** 4,000 cards issued (`CardType`, `IssuedDate`, `ExpirationDate`)
6. **Support Calls:** 3,000 customer service interactions (`IssueType`, `Resolved`)

---

## 🛠️ Tools Used
- **Power BI:** Data modeling, DAX measures, interactive visuals, and custom theme styling.
- **Excel:** Initial data source structure and relational schema.
