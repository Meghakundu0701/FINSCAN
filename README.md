# ⬡ FinScan — SME Financial Health Scanner

FinScan is a multi-dimensional financial intelligence and risk-scoring dashboard designed for Small and Medium Enterprises (SMEs). It evaluates business health across profitability, liquidity, regulatory compliance, transaction patterns, and operational maturity to provide a comprehensive, real-time risk assessment.

👉 **Live Demo:** [Streamlit Community Cloud Link](https://share.streamlit.io/) *(Deploy your fork!)*

---

## ⚡ Key Features

* **📊 Multi-Dimensional Scoring Engine**: Dynamically calculates a **Health Score (0-100)** and letter grade (A+ to F) across five core verticals:
  * **Profitability**: Net profit margins.
  * **Liquidity**: Cash runway and debt-to-revenue leveraging.
  * **Compliance Posture**: GST filing timelines, KYC verification, and AML/audit status.
  * **Transaction Health**: Flags high-value concentrations and international FEMA exposures.
  * **Operational Maturity**: Age of operation, head count, and structural audit history.
* **⚠️ Real-time Anomaly & Risk Flags**: Automatic warning system identifying critical hazards like runway depletion, structuring patterns, regulatory delays, and cash flow strain.
* **📈 12-Month Financial Forecast**: Interactive forecasting simulator projecting Revenue, Expenses, and Net Profits using simulated growth algorithms.
* **🎯 AI-Powered Insights**: Context-aware advisory cards offering prescriptive guidance based on custom business thresholds.
* **💰 Cost Structure & Burn Analysis**: Visual breakdown of operating expenses (Payroll, Tech, Marketing, etc.) alongside key financial indicator gauges.

---

## 🛠️ Technology Stack

* **Frontend Framework**: [Streamlit](https://streamlit.io/) (Highly customized dark theme with CSS overrides)
* **Data Processing**: [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/)
* **Data Visualization**: [Plotly](https://plotly.com/python/) (Radar charts, dual-axis forecasts, bar graphs, and indicator gauges)

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python 3.10+ installed on your system.

### Local Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Meghakundu0701/FINSCAN.git
   cd FINSCAN
   ```

2. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit application**:
   ```bash
   streamlit run sme_scanner.py
   ```

4. Open `http://localhost:8501` in your browser.

---

## ☁️ Deployment

This project is configured to run out-of-the-box on **Streamlit Community Cloud**:

1. Fork this repository.
2. Sign in to [Streamlit Community Cloud](https://share.streamlit.io/).
3. Click **New App**, select your fork, and set the main file path to `sme_scanner.py`.
4. Click **Deploy**!

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
