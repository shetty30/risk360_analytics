# 💼 Financial Risk Management Project

A comprehensive **Python-based risk analytics project** that models and quantifies five core types of financial risk — **Market, Credit, Liquidity, Operational, and Model Risk** — using **Jupyter Notebook**, **NumPy**, **Pandas**, and **Matplotlib**.

---

## 🧩 Project Overview

This project simulates and analyzes the five fundamental categories of risk a financial institution faces.  
Each risk type is modeled with quantitative methods, stress testing, and visualizations for real-world applicability.

| Risk Type | Objective | Key Metrics |
|------------|------------|-------------|
| **Market Risk** | Measure potential losses from market fluctuations | VaR, ES, Volatility, Stress Test |
| **Credit Risk** | Estimate losses from borrower defaults | PD, LGD, EAD, Expected Loss |
| **Liquidity Risk** | Assess ability to meet short-term obligations | LCR, Cashflow Gap, Stress LCR |
| **Operational Risk** | Quantify internal process & system failures | Frequency, Severity, Expected Annual Loss |
| **Model Risk** | Evaluate the reliability of risk models | Accuracy, ROC-AUC, Calibration, Loss Impact |

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:**  
  - `numpy` – numerical simulation  
  - `pandas` – data handling & computation  
  - `matplotlib` – data visualization  
  - `scikit-learn` – model evaluation (ROC, accuracy)


---

## 📊 Key Features

### 🔹 Market Risk
- Simulates daily portfolio returns
- Calculates **Volatility**, **Parametric & Historical VaR (99%)**, and **Expected Shortfall**
- Performs **Stress Testing** for market crashes

### 🔹 Credit Risk
- Simulates loan portfolios with ratings, exposures, and PD/LGD
- Calculates **Expected Loss** and **Portfolio Credit Risk**
- Visualizes **Loss by Credit Rating**

### 🔹 Liquidity Risk
- Analyzes daily **cash inflows, outflows, and LCR**
- Detects **LCR breaches (<100%)**
- Models **stress scenarios** with inflow/outflow shocks

### 🔹 Operational Risk
- Generates **loss event data** over multiple years
- Estimates **frequency & severity** using Poisson and Lognormal models
- Computes **Expected Annual Loss** under base and stress conditions

### 🔹 Model Risk
- Compares **predicted vs actual defaults**
- Calculates **Accuracy, AUC**, and **Calibration**
- Estimates **financial loss impact** from model errors

---

## 📈 Visual Outputs

Includes rich visualizations for:
- Risk distributions (VaR, Expected Loss)
- Liquidity ratio over time
- Operational loss histograms
- Model calibration curve
- Stress vs base scenario comparison



