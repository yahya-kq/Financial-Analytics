# 📉 DCF Valuation – WACC Model

Welcome to my **DCF & WACC Modelling Project**!  
This project demonstrates how to calculate the **Weighted Average Cost of Capital (WACC)** — the foundation of any serious company valuation — using real market data, regression analysis, and peer comparable benchmarking across the **Pakistani fashion & textile sector**.


##  What This Project Covers

- 📊 **Peer Comparable Analysis** — selecting and analyzing 5 listed Pakistani fashion companies
- 📐 **Beta Regression** — calculating Beta using 2 years of weekly stock returns vs market index
- 📈 **Equity Risk Premium** — derived from 22 years of historical market returns (2000–2022)
- 💰 **Cost of Debt** — pre-tax and after-tax cost of debt with tax shield
- 🧮 **Cost of Equity** — using the Capital Asset Pricing Model (CAPM)
- ⚖️ **Capital Structure** — current vs target debt/equity weights
- 🎯 **Final WACC** — combining all components into one discount rate

##  Project Overview

| Detail | Info |
|---|---|
| **Sector** | Fashion & Textile |
| **Market** | Pakistan |
| **Currency** | PKR (Pakistani Rupee) |
| **Tool Used** | Microsoft Excel |


##  Peer Companies Used

| Company | Sector |
|---|---|
| Gul Ahmed | Textile / Fashion |
| Khaadi | Fashion Retail |
| Sapphire Retail Limited | Fashion Retail |
| Sana Safinaz | Fashion Retail |
| Bareezé | Fashion Retail |


## 📈 Key Model Output

| Metric | Value |
|---|---|
| Pre-Tax Cost of Debt | 9.72% |
| After-Tax Cost of Debt | 6.80% |
| Risk Free Rate | 7.39% |
| Equity Risk Premium | 8.02% |
| Levered Beta | 1.68 |
| Cost of Equity (CAPM) | 20.88% |
| Target Debt Weight | 5.94% |
| Target Equity Weight | 94.06% |
| **Final WACC** | **20.04%** |


## 🧠 What I Did in This Project

**Step 1 — Peer Comparables**
Five listed Pakistani fashion and textile companies were selected as peers — Gul Ahmed, Khaadi, Sapphire Retail, Sana Safinaz, and Bareezé. Their total debt, market capitalization, and tax rates were used to calculate Levered and Unlevered Betas for each peer.

**Step 2 — Beta via Regression**
Instead of using a simple published Beta, I ran a **manual linear regression** in Excel using 2 years of weekly stock returns against the market index — 104 data points in total. The raw Beta was then adjusted using the Blume adjustment formula to arrive at the final **Adjusted Beta**.

**Step 3 — Equity Risk Premium**
Historical annual market returns from **2000 to 2022** were collected and averaged to calculate the market's long-run expected return, which was then used to derive the **Equity Risk Premium (ERP)**.

**Step 4 — Cost of Equity (CAPM)**
Using the Risk-Free Rate, ERP, and the re-levered Beta based on the target capital structure, the **Cost of Equity** was calculated at **20.88%** using the CAPM formula.

**Step 5 — Cost of Debt**
The pre-tax cost of debt was identified and adjusted for the corporate tax rate (30%) to arrive at an **after-tax cost of debt of 6.80%**.

**Step 6 — Final WACC**
The Cost of Equity and Cost of Debt were weighted using the **target capital structure** to produce a final **WACC of 20.04%** — ready to be used as the discount rate in a full DCF valuation.


## 💡 Who Is This For?

👨‍🎓 **Finance & Accounting Students** — If you're studying corporate valuation, this gives you a real, hands-on WACC model built on actual Pakistani market data.

📊 **Aspiring Equity Analysts** — Building WACC from scratch using regression and peer comps is a core skill in investment banking, equity research, and corporate finance.

🧑‍💼 **Finance Professionals** — A clean reference model for structuring your own WACC calculations for any company or sector in Pakistan or beyond.


##  How You Can Apply This

- Use this as a **template** to calculate WACC for any listed company in Pakistan or any other market
- Swap the peer companies to apply it to a **different sector** — banking, energy, FMCG, etc.
- Extend the model by building the **full DCF** on top — projecting free cash flows and discounting them at this WACC to find intrinsic value
- Practice running your own **Beta regression** using historical price data from the PSX or Bloomberg
- Use it as a reference when preparing for **investment banking, CFA, or equity research interviews**


##  Tools & Skills Applied

- **Microsoft Excel** — regression analysis, financial modelling, and WACC calculation
- **Beta Regression** — 2-year weekly return regression against market index (104 observations)
- **Blume Adjustment** — adjusting raw Beta toward the market mean
- **CAPM** — Capital Asset Pricing Model for Cost of Equity
- **Peer Comparable Analysis** — unlevering and re-levering Beta across industry peers
- **Capital Structure Analysis** — current vs target weights for debt and equity


##  Other Projects

Explore my other repositories for more finance, analytics, and data projects:

| Repository | Description |
|---|---|
| [📊 BI Solutions](https://github.com/yahya-kq/BI-Solutions) | Business Intelligence dashboards and reporting |
| [📗 Excel Analytics](https://github.com/yahya-kq/Excel-Analytics) | Data analysis and automation using Excel |
| [🛢 SQL Projects](https://github.com/yahya-kq/Sql-Projects) | Database querying and data analysis with SQL |
| [💰 Financial Analytics](https://github.com/yahya-kq/Financial-Analytics) | Financial data analysis and modeling |
| [🔬 Advance Analytics](https://github.com/yahya-kq/Advance-Analytics) | Advanced analytical techniques and projects |


##  Author

**Yahya Qureshi**

| | |
|---|---|
| 📧 Email | [yahyaqureshi012@gmail.com](mailto:yahyaqureshi012@gmail.com) |
| 🌐 Portfolio | [yahya-kq.odoo.com](https://yahya-kq.odoo.com/) |
| 🐙 GitHub | [github.com/yahya-kq](https://github.com/yahya-kq) |
| 💼 LinkedIn | [linkedin.com/in/yahya-kq](https://www.linkedin.com/in/yahya-kq) |



⭐ Found this helpful? Give the repo a star and share it with others!
