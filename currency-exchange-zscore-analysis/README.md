# 📈 Z-Score Normalized Currency Exchange Rate Analysis

This project visualizes the exchange rate trends of five major global currencies — **CNY, GBP, INR, JPY, and USD** — over time using **Z-score normalization**. The visualization was created using Tableau Public and highlights volatility patterns, macroeconomic anomalies, and relative valuation changes.

---

## 🧠 Objective

To compare fluctuations in exchange rates by removing scale bias using Z-scores. This allows us to focus on **deviation from the mean** for each currency, enabling fair cross-currency comparison.

---

## 📊 Methodology

- **Tool Used:** Tableau Public
- **Dataset:** `currency_focus_raw.csv` (12 months of daily exchange rate data)
- **Transformation:**  
  Z-Score =  
  \[
  \frac{\text{Exchange Rate} - \text{Mean}}{\text{Standard Deviation}}
  \]
  Applied using Tableau table calculations.

---

## 🔍 Key Insights

- **All currencies** start significantly **above their average (Z > 1.5)** in August 2024, suggesting a brief overvaluation period.  
- **JPY** shows the **most extreme and frequent deviations**, often spiking above +2.5 and falling below -1.5 — signaling high sensitivity to global macro events.  
- **GBP** trends upward through mid-2025, peaking above +1.5, reflecting sustained appreciation.  
- **INR and CNY** remain within ±1 Z-score — possibly indicating central bank intervention or stable policy.  
- **By July 2025**, all currencies converge near Z = 0, suggesting **mean reversion** across markets.

---

## 📷 Preview

![Dashboard Screenshot](dashboard_screenshot.png)

---

## 📁 Files

- `currency_focus_raw.csv`: Input dataset
- `dashboard_screenshot.png`: Tableau Z-score dashboard
