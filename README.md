## 📄 Quick Access
>* **[Google Colab (Backup)](https://colab.research.google.com/github/ziadnasr2007/Suez-Dutch_disease-Egypt/blob/main/Projectt.ipynb)**.
>* **[Download Research PDF (Recommended)](./Suez_Dutch_Disease_Research.pdf)** - *Best for a quick review of results and graphs.*
# Suez-Dutch_disease-Egypt.
An econometric analysis of Dutch disease in Egypt: Quantifying the Transmission of Suez Canal Rents to the Industrial Sector via REER Volatility (VECM Approach).
# Suez Canal Rents and Dutch Disease in Egypt (2016-2024)

## Project Overview
This repository contains an econometric investigation into the presence of **Dutch Disease** in the Egyptian economy. Using a **Vector Error Correction Model (VECM)**, this study analyzes how fluctuations in Suez Canal revenues impact the Real Effective Exchange Rate (REER) and subsequently influence manufacturing sector output.

## Key Findings
* **Transmission Channel:** Suez Canal revenues are identified as a dominant structural anchor for the EGP.
* **Currency Volatility:** Suez shocks explain **29.4%** of the variance in the REER by the 4th quarter.
* **Industrial Impact:** While the direct link is negligible, the exchange rate channel (driven by Suez) accounts for **7.0%** of total manufacturing output volatility.
* **Weak Exogeneity:** Statistical tests ($p=0.239$) confirm that Suez revenues act as a truly exogenous resource rent shock.

## Methodology
* **Model:** 4-Variable VECM (Suez, REER, Manufacturing, CPI).
* **Data:** Quarterly observations (2016-2024) sourced from the Central Bank of Egypt and CAPMAS.
* **Transformations:** Log-log specification to measure constant elasticity.

## How to Run
1.  Clone the repository.
2.  Ensure `pandas`, `numpy`, and `statsmodels` are installed.
3.  Open `Suez_Dutch_Disease_Analysis.ipynb` in Jupyter Notebook.
