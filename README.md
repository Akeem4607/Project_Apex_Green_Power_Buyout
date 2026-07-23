
# Project Apex: GreenPower Motor Company Distressed Buyout & Turnaround Valuation
## 📌 Project Overview
This repository contains the final  project for the **Coursera Financial Analysis and Modeling** specialization. The project simulates a private equity acquisition and turnaround proposal for **GreenPower Motor Company** (NASDAQ: GP), a distressed micro-cap electric vehicle manufacturer trading at $1.19 per share. 
The objective of this analysis is to evaluate whether an acquisition can create value under strict operational restructuring and discounted entry valuations.
---
## 📊 Key Deliverables & Repository Structure
- **`models/GreenPower_DCF_Valuation_Model.xlsx`**: Fully integrated DCF financial model featuring:
  - CAPM-derived WACC estimation ($11.5\%$ blended cost of capital).
  - 5-year ratio-to-sales FCF projections under a Turnaround operating scenario.
  - Gordon Growth terminal value calculation ($1.5\%$ terminal growth rate).
  - Enterprise-to-Equity Value bridge and dynamic debt adjustments ($\sim \$19.9\text{M}$ debt).
  - Multi-scenario comparison matrix (Downside, Base Case, Turnaround).
  - Two-way sensitivity analysis table evaluating WACC vs. Terminal Growth.
- **`reports/GreenPower_Valuation_Summary.docx`**: Two-page executive valuation summary document.
- **`reports/GreenPower_Investment_Recommendation.docx`**: Final investment committee decision memo outlining risks, value creation levers, and deal terms.
---
## 📈 Valuation Summary & Scenarios

| Operating Scenario | Core Assumptions | Implied Equity Value / Share | Upside / Downside vs. $1.19 Price |
| :--- | :--- | :--- | :--- |
| **Downside Case** | Revenue $-10\%$ CAGR, SG&A at $90\%$ | **$0.20** | $-83.2\%$ |
| **Base Case** | Revenue flat ($0\%$), SG&A at $50\%$ | **$1.50** | $+26.1\%$ |
| **Turnaround Case** | Revenue $+15\%$ CAGR, COGS $80\%$, SG&A $25\%$ | **$3.50** | $+194.1\%$ |

---
## 🛠️ Financial Modeling Methodologies Used
- **Cost of Capital (WACC):** Risk-free rate ($4.0\%$), ERP ($5.0\%$), Beta ($1.80$), Cost of Equity ($13.0\%$), Pre-tax Cost of Debt ($12.0\%$ based on MD&A related-party loans).
- **Operating Turnaround Lever:** Scaling manufacturing capacity while rationalizing SG&A expenses down from $>100\%$ to $25\%$ of revenue.
- **Risk Mitigation:** Establishing a hard valuation ceiling of **$1.00 per share** (with target entry at **$0.60–$0.75**) to protect against execution risk and debt overhang.
