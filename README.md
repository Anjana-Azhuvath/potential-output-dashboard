# 🇮🇳 Potential Output & Business Cycle Dashboard

An interactive Python dashboard and Colab notebook for analyzing India's real GDP, estimating potential output via the Hodrick–Prescott (HP) filter, and visualizing business cycles.

---

## 📊 Overview

This project decomposes Real GDP into **Trend (Potential GDP)** and **Cycle (Output Gap)** components using the **HP filter**, then visualizes:
- Actual vs Potential GDP
- Output Gap (business cycle)
- Quarterly (QoQ) and Year-over-Year (YoY) growth rates
- Rolling 4-year CAGR of GDP

---

## 🧰 Features

- HP filter decomposition using `statsmodels`
- Computation of:
  - QoQ and YoY growth rates  
  - Output gap (% deviation from potential GDP)  
  - Rolling CAGR and potential growth  
- Interactive Plotly visualizations
- Summary statistics and macroeconomic interpretation
- Streamlit web dashboard **and** Colab notebook versions

---

## 🚀 Quick Start

### Option 1 – Run in Google Colab

Open the Colab notebook:

```python
# In a Colab cell
!git clone https://github.com/<your-username>/potential-output-dashboard.git
%cd potential-output-dashboard/notebooks
