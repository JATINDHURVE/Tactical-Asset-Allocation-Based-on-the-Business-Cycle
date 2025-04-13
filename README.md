# 🧭 Tactical Asset Allocation Based on the Business Cycle

**Short Description:**  
This project presents a tactical asset allocation model that dynamically adjusts portfolio weights based on business cycle phases. Developed as part of the Master of Finance program at Frankfurt School, it integrates macroeconomic and market indicators to optimize allocations across equities, bonds, commodities, and gold—aiming for consistent, risk-adjusted outperformance over time.

---

### 🏫 Conducted at  
**Frankfurt School of Finance and Management**  
Company Project with **HQ Trust** | October 30, 2024



📌 This project was created as part of an academic course at Frankfurt School of Finance and Management. It is shared here for educational and portfolio purposes only.
---

## 📁 Project Structure

- `hq_trust_saa-Copy1.ipynb`: Main Jupyter notebook implementing the full tactical allocation strategy, backtests, performance evaluation, and visualizations.
- `HQ Trust Tactical Asset Allocation Case.pdf`: Official case study brief and task outline.

---

## 📌 Project Goals

**Objective:**  
Develop a dynamic tactical asset allocation strategy that adjusts monthly based on the current phase of the business cycle.

### Key Steps:

1. **Business Cycle Identification**  
   - Analyze macroeconomic indicators: GDP, inflation, unemployment, yield curve, etc.
   - Classify economic phases: Recovery, Boom, Contraction, Recession.

2. **Realistic Data Handling**  
   - Only use data that would have been available at the time.
   - Account for timing of indicator releases and data revisions.

3. **Asset Class Analysis**  
   - Evaluate performance of:
     - MSCI World (Equities)  
     - Rex 10Y Index (Long Bonds)  
     - 3M German Bills (Cash/Short Bonds)  
     - GSCI (Commodities)  
     - Gold  
   - Study how each asset performs across economic phases.

4. **Tactical Allocation Model**  
   - Adjust benchmark weights by ±15% based on the economic phase.
   - No leverage or short-selling; portfolio weight always equals 100%.
   - Incorporate both economic and market-based indicators (e.g., momentum, yield spreads, volatility).

5. **Duration Management**  
   - Adjust duration in the bond portfolio based on yield curve shape and interest rate trends.

6. **Backtesting & Evaluation**  
   - Backtest strategy vs. benchmark (60/25/5/5/5).
   - Evaluate across full period (1973–2024) and individual business cycles.
   - Emphasize robustness, especially in recent 3 years.

7. **Reporting & Recommendations**  
   - Final report summarizes results, model logic, limitations, and real-world investment implications.
   - Key findings prepared for presentation format.

---

## 🛠️ Technologies Used

- **Python** (Jupyter Notebook)
- `pandas`, `numpy`, `matplotlib`, `statsmodels`, `scikit-learn`
- Financial indicators & macroeconomic modeling
- Time series data management and backtesting

---

## 📈 Strategy Highlights

- Systematic reallocation based on business cycle signals
- Multi-decade backtest with macroeconomic context
- Clear improvement in risk-adjusted returns vs. static SAA
- Robust outperformance even in out-of-sample periods

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/yourusername/hq-tactical-allocation.git
cd hq-tactical-allocation
