# Market Risk Projects — Python

Risk analytics projects built with Python, pandas, and real NSE market data.
Author: Mahek | FRM Certified | Operations Risk → Market Risk

---

## Projects

### 1. Portfolio Risk Analyser
**File:** `portfolio_risk_analyser.py`  
**Stocks:** RELIANCE, TCS  
**Period:** 2023–2024  

Historical VaR engine for a 2-stock NSE portfolio.
- 95% & 99% Historical VaR in rupee terms
- 21-day rolling volatility
- Return correlation analysis
- Portfolio diversification effect

---

### 2. Multi-Method VaR Engine
**File:** `multi_method_var_engine.ipynb`  
**Stocks:** RELIANCE, TCS, HDFCBANK, INFY, ICICIBANK  
**Period:** 2023–2024  

Three-method VaR comparison for a 5-stock Nifty portfolio.
- Historical VaR — actual return distribution
- Parametric VaR — normal distribution assumption
- Monte Carlo VaR — 10,000 simulated return paths
- Full method comparison table
- Return distribution visualisation

### 3. FRTB Standardised Approach — Capital Charge Calculator
**File:** `frtb_sa_calculator.ipynb`  
**Stocks:** RELIANCE, TCS, HDFCBANK, INFY, ICICIBANK  

FRTB SA delta sensitivity based capital charge engine for a 5-stock NSE equity book.
- Delta sensitivity calculation per position
- Sector-based risk weight application (Energy, IT, Financials)
- Intra-bucket aggregation across 3 correlation scenarios (high/medium/low)
- Inter-bucket aggregation with prescribed gamma correlation
- Worst case capital charge output
---

## Stack
Python | pandas | NumPy | scipy | yfinance | matplotlib

---

## Contact
[LinkedIn](https://linkedin.com/in/mved)
