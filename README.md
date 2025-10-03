# COVID-19 and MASI Forecasting with ARIMA

This repository contains Jupyter notebooks and code for:
- Short-term forecasting of COVID-19 cases in Morocco
- Forecasting MASI (Moroccan All Shares Index) opening prices
- Model diagnostics, confidence intervals, and residual analysis

## Repository Structure
- `data/` – raw data files (`Morocco.xlsx`, `masi.csv`)
- `notebooks/` – main analysis notebook (`cases_arima_analysis.ipynb`)
- `src/` – optional helper scripts
- `requirements.txt` – dependencies

## Reproducibility
To reproduce results:
```bash
git clone https://github.com/AmoesaAI/covid-masi-arima.git
cd covid-masi-arima
pip install -r requirements.txt
jupyter notebook notebooks/cases_arima_analysis.ipynb
