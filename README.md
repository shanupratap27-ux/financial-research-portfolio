# Financial Research & Econometric Modeling Portfolio

Welcome to my financial research portfolio, featuring empirical time-series econometrics and equity research sector benchmarking.

---

## 📊 Project 1: Macroeconomic Shocks & NSE Sectoral Stock Returns
**Type:** Empirical Master's Dissertation | Econometric Analysis  
**Focus:** Nifty Bank, Nifty IT, Nifty FMCG, and Nifty Auto  
**Sample Horizon:** 120 monthly observations (September 2011 – May 2023)  

### Key Methodology & Econometric Framework
- **Data Architecture:** 30-sheet structured dataset (`Final_Dissertation_Dataset_With_IRF_Final.xlsx`) tracking sectoral returns against CPI inflation, 10Y G-Sec yield, Brent crude returns, USD/INR, and India VIX.
- **Ordinary Least Squares (OLS):** Evaluated baseline sensitivity and systematic beta linkages across sectors.
- **Quantile Regressions ($Q_{0.05} - Q_{0.95}$):** Tested asymmetric, state-dependent exposure across weak, median, and strong market environments.
- **Vector Autoregression (VAR) & Impulse Response Functions (IRF):** Modeled dynamic shock persistence and normalization horizons over a 10-month window.

### Primary Empirical Findings
- **Broad Market Beta:** Nifty 50 is the dominant systematic driver across all four sectors ($\beta$ from 0.539 for IT to 1.511 for Banking).
- **Asymmetric Inflation Risk (Banking):** Banking returns drop significantly under inflationary pressure ($\beta = -1.335, p = 0.014$), with vulnerability concentrating in lower and median return quantiles.
- **Crude Oil Pass-Through (FMCG):** FMCG exhibits a statistically significant negative drag from crude oil returns ($\beta = -0.066, p = 0.026$), which intensifies in the 5th percentile ($Q_{0.05} = -0.139$).
- **Dynamic Shock Normalization:** Impulse response trajectories reveal macro shocks are short-run and converge back toward equilibrium within 4–5 months.

---

## 🏭 Project 2: Indian Wires & Cables Industry Deep Dive
**Type:** Institutional Sector Research & Equity Valuation  
**Institution:** Nirmal Bang  
**Companies Benchmarked:** Polycab India, KEI Industries, RR Kabel, Havells India, Finolex Cables  

### Strategic & Financial Analysis
- **Structural Shifts:** Sector formalization from unorganized trade to branded play (branded market share up from 60% in FY15 to 76% in FY23; projected 82% by FY27).
- **Capex Catalysts:** Transmission & Distribution modernization (RDSS), renewable energy integration (500 GW target by 2030), EV charging infrastructure, and hyperscale data center rollouts.
- **Financial Benchmarking:** Evaluated raw material sensitivity (copper/aluminium accounting for 60–70% of cost structure), working capital cycle efficiency, and ROCE/ROE trajectories across distribution channels.

---

## 📁 Repository Contents
- `Final_Dissertation_Dataset_With_IRF_Final.xlsx`: Full 30-sheet model with raw prices, returns, OLS outputs, quantile tables, and IRF matrices.
- `Shanu_Singh_590010710_Dissertation_MBA_Finance.pdf`: Complete 35-page empirical research dissertation.
- `A Summer Internship Project Report On (AutoRecovered).pdf`: Complete 64-page wires and cables sector report.
