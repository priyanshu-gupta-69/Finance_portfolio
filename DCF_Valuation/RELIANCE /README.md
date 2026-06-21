# 📊 Reliance Industries Limited (RIL) DCF Valuation | FY2025

> A comprehensive **Discounted Cash Flow (DCF)** valuation model for **Reliance Industries Limited (RIL)** based on FY2025 financial statements and annual report data.

---

## 🎯 Objective

The objective of this project is to estimate the **intrinsic value per share** of Reliance Industries Limited using the **Discounted Cash Flow (DCF)** valuation method.

The model combines:

* Historical financial analysis
* Key valuation assumptions
* 5-year financial projections
* Free Cash Flow estimation
* Terminal Value calculation
* Sensitivity Analysis

The final output is an estimate of **fair value per share**, which can be compared with the market price.

---

# 📖 Overview

DCF (Discounted Cash Flow) is one of the most widely used valuation methods in corporate finance and equity research.

This project:

✅ Analyzes FY2023 to FY2025 historical financials
✅ Forecasts FY2026 to FY2030 performance
✅ Discounts future cash flows using WACC
✅ Calculates Terminal Value using the Gordon Growth Model
✅ Estimates Enterprise Value, Equity Value and Intrinsic Value per Share

---

# 🏢 Company Information

| Item           | Details                     |
| -------------- | --------------------------- |
| Company        | Reliance Industries Limited |
| Ticker         | RELIANCE                    |
| Exchange       | NSE / BSE                   |
| Industry       | Conglomerate                |
| Financial Year | FY2025 (March 31, 2025)     |
| Currency       | ₹ Crores                    |

---

# 📂 Data Source

This valuation model uses publicly available financial data from:

* Reliance Industries FY2025 Annual Report
* Official Company Website
* NSE India filings
* Investor Presentations

**Currency:** ₹ Crores

---

# ⚙️ Methodology

The DCF model follows these steps:

### 1. Historical Analysis (FY2023 - FY2025)

Analyze:

* Revenue
* Operating Expenses
* EBITDA
* EBIT
* Tax Expense
* Net Income
* Operating Cash Flow
* Capital Expenditure
* Free Cash Flow

---

### 2. Build Assumptions

Estimate key drivers:

* Revenue Growth Rate
* EBITDA Margin
* Tax Rate
* CapEx as % of Revenue
* Working Capital as % of Revenue
* WACC
* Terminal Growth Rate

---

### 3. Financial Projections (FY2026 - FY2030)

Project:

* Revenue
* EBITDA
* PAT
* Free Cash Flow

using historical trends and assumptions.

---

### 4. Discount Future Cash Flows

Discount projected cash flows using:

**Discount Factor**

```text
1 / (1 + WACC)^n
```

where:

* n = Year number
* WACC = Weighted Average Cost of Capital

---

### 5. Terminal Value

Terminal Value is estimated using the **Gordon Growth Model**:

```text
TV = FCF × (1 + g) / (WACC - g)
```

where:

* FCF = Free Cash Flow in final forecast year
* g = Terminal Growth Rate

---

### 6. Intrinsic Value Per Share

Finally,

```text
Equity Value = Enterprise Value - Net Debt

Intrinsic Value per Share
= Equity Value / Shares Outstanding
```

---

# 📁 Project Structure

```text
RELIANCE/

├── README.md

├── Annual_Report/

│   └── Reliance_FY2025_Annual_Report.pdf

│

├── Excel_Model/

│   └── Reliance_DCF_Model_FY2025.xlsx

│

└── Investor_Presentation/

    └── (Future PPT/PDF)
```

---

# 📘 Excel Workbook Details

## 1. Historical_Financials

Contains:

* FY2023
* FY2024
* FY2025

Data:

* Revenue
* EBITDA
* EBIT
* Tax Expense
* Operating Cash Flow
* CapEx
* Free Cash Flow

Purpose:

Establish historical trends used in forecasting.

---

## 2. Assumptions

Contains all key valuation inputs.

### Color Coding

🟦 **Blue** → User Inputs

🟩 **Green** → Formula Cells

Examples:

* Revenue Growth
* EBITDA Margin
* Tax Rate
* WACC
* Terminal Growth

---

## 3. Projections

Forecasts:

**FY2026 → FY2030**

Projects:

* Revenue
* EBITDA
* PAT
* Free Cash Flow

based on assumptions and historical trends.

---

## 4. DCF_Valuation

Core valuation sheet.

Calculates:

* PV of Future FCF
* Terminal Value
* Enterprise Value
* Net Debt
* Equity Value
* Intrinsic Value per Share

🔴 Final outputs are highlighted in **Red + Bold**.

---

## 5. Sensitivity_Analysis

Analyzes how valuation changes under different assumptions.

Rows:

* WACC (9%-13%)

Columns:

* Terminal Growth (1%-5%)

Output:

* Intrinsic Value per Share under each scenario

---

# 📈 Key Metrics

| Metric                    | Value |
| ------------------------- | ----: |
| Intrinsic Value per Share |   TBD |
| Valuation Range           |   TBD |
| Current Market Price      |   TBD |
| Upside / Downside         |   TBD |

*Values will be updated after populating the final FY2025 model.*

---

# 🚀 How to Use

### Step 1

Open:

```text
Excel_Model/

Reliance_DCF_Model_FY2025.xlsx
```

---

### Step 2

Go to:

```text
Assumptions
```

Review the **blue cells**:

* Revenue Growth
* EBITDA Margin
* Tax Rate
* WACC
* Terminal Growth

---

### Step 3

Open:

```text
Projections
```

Review FY2026-FY2030 forecasts.

---

### Step 4

Go to:

```text
DCF_Valuation
```

Check:

* Enterprise Value
* Equity Value
* Intrinsic Value per Share

The final output is highlighted in **Red**.

---

### Step 5

Open:

```text
Sensitivity_Analysis
```

Review valuation ranges under different WACC and growth assumptions.

---

# 🔑 Key Assumptions

| Assumption        | Why it Matters                       |
| ----------------- | ------------------------------------ |
| Revenue Growth    | Drives future earnings               |
| EBITDA Margin     | Measures operating profitability     |
| Tax Rate          | Impacts after-tax cash flows         |
| CapEx % Revenue   | Determines reinvestment requirements |
| Working Capital % | Impacts cash generation              |
| WACC              | Discount rate for future cash flows  |
| Terminal Growth   | Determines long-term value           |

---

# ⚠️ Limitations

This model has several limitations:

* DCF valuation is highly sensitive to assumptions.
* Terminal Value contributes a significant portion of total valuation.
* Future acquisitions or divestitures are not considered.
* Market prices may deviate from intrinsic value due to investor sentiment.
* The model assumes relatively stable long-term operations.

---

# 📌 Next Steps

Potential future improvements:

* Compare intrinsic value with market price
* Add Bull / Base / Bear scenarios
* Include scenario-based sensitivity analysis
* Build investment thesis and recommendation
* Automate data collection using Python

---

# ✅ Status

| Task                  | Status        |
| --------------------- | ------------- |
| Historical Financials | ✅ Completed   |
| Assumptions           | ✅ Completed   |
| Projections           | ✅ Completed   |
| DCF Model             | ✅ Completed   |
| Sensitivity Analysis  | ⏳ In Progress |
| Scenario Analysis     | ⏳ Planned     |

---

## 👨‍💻 Author

**Priyanshu Gupta**

📅 Date: June 20, 2026

🔗 LinkedIn: www.linkedin.com/in/priyanshudcac

💻 GitHub: https://github.com/priyanshu-gupta-69

---

⭐ If you found this project interesting, feel free to explore the repository and connect with me.

