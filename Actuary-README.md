
# 📊 Insurance Claims Economic Modeling & Risk Simulation

This project builds a modular, Python-based economic model that ingests actuarial and insurance datasets to simulate how economic conditions (like inflation, interest rates, or claim severity) affect reserves, profitability, and risk capital. It leverages tools like **Python (PyCharm)**, **Excel**, and **GitHub**, and uses publicly available datasets from CAS, Allstate, SOA, CMS, and DataRobot.

---

## 🎯 Project Goals

- Forecast future claims and reserves using development triangles
- Apply economic adjustments (inflation, interest rate, discounting)
- Simulate scenarios to assess surplus, reserve adequacy, and capital risk
- Compare and validate results using Excel
- Present findings using charts and Excel summaries
- Share modular, reproducible code via GitHub

---

## 🛠 Tools & Technologies

- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels
- **PyCharm**: Python development IDE
- **Excel**: Reporting, visualization, scenario comparison
- **GitHub**: Version control and documentation

---

## 📂 Project Structure

```
insurance-economic-model/
├── data/                         # Source datasets
│   ├── CAS_Auto.csv
│   ├── allstate_claims.csv
│   ├── synthetic_claims.csv
│   ├── cms_provider_data.csv
│   └── soa_auto_insurance.csv
│
├── notebooks/                    # Jupyter notebooks for exploration & modeling
│   ├── exploratory_CAS.ipynb
│   ├── model_allstate.ipynb
│   ├── economic_impact_simulations.ipynb
│
├── src/                          # Python modules
│   ├── loader.py
│   ├── chain_ladder.py
│   ├── economic_adjustment.py
│   ├── scenario_engine.py
│   └── excel_exporter.py
│
├── output/                       # Excel exports & graphs
│   ├── reserve_forecasts.xlsx
│   ├── scenario_summary.xlsx
│   └── graphs/
│       ├── cas_triangle.png
│       └── inflation_vs_surplus.png
│
├── README.md
└── requirements.txt
```

---

## 📊 Datasets Used

- [CAS Loss Reserving Database](https://github.com/CAS-Actuarial-Society/Loss-Reserve-Database)
- [Allstate Claims Severity Dataset](https://www.kaggle.com/competitions/allstate-claims-severity)
- [Synthetic Insurance Data (DataRobot)](https://community.datarobot.com/t5/resources/synthetic-insurance-data-set/ba-p/2703)
- [CMS Medicare Provider Utilization](https://data.cms.gov/provider-summary-by-type-of-service/medicare-physician-other-practitioners/medicare-provider-utilization-and-payment-data-physician-and-other-practitioners)
- [SOA Public Datasets](https://www.soa.org/resources/data-research/)

---

## 🧠 Key Modules

- `chain_ladder.py`: Implements reserve forecasting using the Chain Ladder method
- `economic_adjustment.py`: Applies inflation, interest rates, and discounting
- `scenario_engine.py`: Runs economic simulations (e.g., inflation shock, low interest)
- `excel_exporter.py`: Exports results and tables for review

---

## 🧪 How to Run

1. Clone this repo:
    ```bash
    git clone https://github.com/your-username/insurance-economic-model.git
    cd insurance-economic-model
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter or PyCharm to run notebooks or scripts:
    - `notebooks/exploratory_CAS.ipynb` – first triangle model
    - `notebooks/economic_impact_simulations.ipynb` – run inflation/interest scenarios

4. Review Excel and graph outputs in the `/output` folder

---

## 📈 Sample Visuals (Placeholder)

> ![cas_triangle](output/graphs/cas_triangle.png)  
> ![inflation_vs_surplus](output/graphs/inflation_vs_surplus.png)

---

## 👨‍💼 Author

Neil Dalal  
Finance–Technology Leader | Futures Trader | Insurance Modeling Expert  
📫 dalal.neil@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/neildalal1)

---
