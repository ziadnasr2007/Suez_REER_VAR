# Suez Canal Rents and Dutch Disease in Egypt (2016–2024)

## 📄 Quick Access
- **[Download Research PDF (Recommended)](./ProjecttGithub.pdf)**  
  *Best for a concise review of results, tables, and impulse-response figures.*
- **[Open in Google Colab](https://colab.research.google.com/github/ziadnasr2007/Suez-Dutch_disease-Egypt/blob/main/Projectt.ipynb)**  
  *Recommended for technical auditing and full code replication.*

---

## 🔬 Project Overview
This repository presents an econometric investigation into the presence of **Partial Dutch Disease** in the Egyptian economy. Using a **Vector Error Correction Model (VECM)**, the study examines how fluctuations in **Suez Canal revenues** influence the **Real Effective Exchange Rate (REER)** and, through it, the performance of the **manufacturing sector**.

Rather than testing for a full deindustrialization mechanism, the analysis focuses on whether Suez Canal rents generate a **currency-mediated spending effect**, consistent with modern Dutch Disease frameworks.

---

## 🔑 Key Findings
- **Transmission Channel:**  
  Suez Canal revenues act as a dominant structural anchor for the Egyptian pound, explaining **29.4% of REER volatility** by the fourth quarter.

- **Secondary Industrial Impact:**  
  REER movements driven by Suez revenue shocks account for **7.0% of manufacturing output volatility**, indicating **partial** rather than destructive Dutch Disease pressures.

- **Direct vs. Indirect Effects:**  
  The negligible direct impact on manufacturing (**1.1%**) confirms that the channel operates almost entirely through **exchange-rate appreciation (Spending Effect)** rather than labor reallocation (**Resource Movement Effect**).

---

## 📊 Data & Methodology

### Data Sources
- **Suez Canal Revenues & REER:** Central Bank of Egypt (CBE), Monthly Statistical Bulletin  
- **Manufacturing Output & CPI:** CAPMAS (Central Agency for Public Mobilization and Statistics)  
- **Frequency:** Quarterly data from **2016 Q3 to 2024 Q2**

---

### Econometric Robustness

| Test | Result | Interpretation |
|:---|:---|:---|
| **ADF Unit Root Tests** | All variables are *I(1)* | Supports cointegration analysis |
| **Johansen Trace Test** | *r = 1* (p < 0.05) | One stable long-run relationship |
| **Lag Selection** | 2 lags (AIC) | Optimal balance of fit and parsimony |
| **Durbin–Watson Statistic** | ≈ 2.0 (all equations) | No residual autocorrelation; IRFs valid |

---

## 🛠️ Getting Started

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ziadnasr2007/Suez-Dutch_disease-Egypt.git
```

2. Navigate to the project directory:

   ```bash
   cd Suez-Dutch_disease-Egypt
   ```
3. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

### Replicating the Results

1. Launch Jupyter Notebook (or open the notebook via Google Colab).
2. Open `Projectt.ipynb`.
3. From the menu, select **Cell → Run All**.

Running all cells will:

* Reproduce the **Impulse Response Functions (IRFs)**
* Generate the **Forecast Error Variance Decomposition (FEVD)**
* Replicate all figures and tables reported in `ProjecttGithub.pdf`
