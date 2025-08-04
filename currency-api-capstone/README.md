# Currency API Capstone

This project uses the Frankfurter API to fetch historical currency exchange rates between USD and other major currencies for the past one year, and builds on that data for further analysis and dashboarding.

---

## 📌 Objective

- Extract reliable historical exchange rate data
- Store and structure the data in CSV format
- Lay the foundation for exploratory analysis, cost forecasting, or visual dashboards
- **Visualize relative currency performance using Z-score normalization**

---

## 📁 Files Included

- `fetch_currency_data.ipynb` – Python notebook to call the API and save data
- `currency_rates.csv` – Output dataset of daily exchange rates
- `clean_currency_rates.csv` – Cleaned version for analysis
- `currency_focus_zscore.csv` – Z-score normalized version of exchange rates
- `currency_focus_raw.csv` – Raw input used in Tableau

---

## 📊 Z-Score Dashboard (Subproject)

📂 `currency-exchange-zscore-analysis`  
This subfolder contains a Tableau dashboard visualizing how far each currency deviates from its own 12-month average using Z-scores. This enables a standardized comparison across different currencies with different baselines.

### 🔍 Key Insights:
- August 2024 saw strong overvaluation across all currencies (Z > 1.5)
- JPY showed high volatility, swinging beyond ±2.5 frequently
- GBP appreciated consistently, while INR and CNY stayed relatively stable
- By July 2025, most currencies mean-reverted near Z = 0

📸 See `Dashboard_screenshot.png` in the folder for the visualization.

---

## 🧰 Tools Used

- Python (Frankfurter API, pandas)
- Tableau Public
