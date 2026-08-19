# 🏦 Loan & EMI Calculator 📊

An interactive, browser-based financial tool designed to calculate Equated Monthly Installments (EMIs), total interest accrual, and full loan repayment amounts using reducing-balance compound interest logic.

🔗 **[Live Demo](https://ng410782-cell.github.io/loan-emi-calculator/)**

---

## 🌟 Key Features

- **Reducing-Balance EMI Calculation:** Uses standard commercial banking formulas to calculate precise monthly repayments.
- **Financial Breakdown:** Displays monthly EMI, total interest payable over the loan tenure, and overall repayment amount.
- **Indian Currency Formatting:** Automatically formats calculations using the standard Indian numbering system (`₹`).
- **Input Validation:** Prevents invalid or non-numeric values to ensure accurate computations.
- **Zero Dependencies:** Pure HTML5, CSS3, and JavaScript—loads instantly in any web browser without installation.

---

## 📐 Financial Logic & Formulas

The calculator applies the standard reducing-balance EMI formula used by financial institutions:

$$E = P \times r \times \frac{(1 + r)^n}{(1 + r)^n - 1}$$

**Where:**
- $E$ = Equated Monthly Installment (EMI)
- $P$ = Principal Loan Amount
- $r$ = Monthly Interest Rate ($\frac{\text{Annual Rate}}{12 \times 100}$)
- $n$ = Loan Duration in Months ($\text{Tenure in Years} \times 12$)

### Repayment Calculations:
* **Total Amount Payable:** $E \times n$
* **Total Interest Payable:** $(\text{Total Amount Payable}) - P$

---

## 🚀 How to Run Locally

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/ng410782-cell/loan-emi-calculator.git](https://github.com/ng410782-cell/loan-emi-calculator.git)
