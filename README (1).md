# Regional Sales Analytics & Dashboard 📊

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebooks-orange?logo=jupyter)
![Power BI](https://img.shields.io/badge/Power BI-Dashboard-yellow?logo=powerbi)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

---

## 🚀 Project Overview
This repository transforms raw regional sales spreadsheets into **data‑driven insight** and a shareable, interactive **Power BI dashboard**.  
We:

1. **Clean & Wrangle** data in Python (`cleaning-&-wrangling.ipynb`).
2. **Explore & Visualize** with Jupyter (`EDA.ipynb`).
3. **Produce** a polished **`sales_data_cleaned.xlsx`** dataset.
4. **Build** an interactive dashboard in **Power BI** (`SALES REPORT.pbix`).

The result is a single source‑of‑truth for regional sales performance that business users can slice, drill, and filter.

---

## 🗂️ Repository Structure

```text
├── data/
│   ├── final_sales_data.xlsx          # Final curated dataset
│   ├── Regional Sales Dataset.xlsx    # Raw source data
│   └── sales_data_cleaned.xlsx        # Cleaned, analysis‑ready data
│
├── notebooks/
│   ├── cleaning-&-wrangling.ipynb     # Data wrangling pipeline
│   └── EDA.ipynb                      # Exploratory analysis & visuals
│
├── dashboard/
│   └── SALES REPORT.pbix              # Power BI interactive dashboard
│
└── README.md                          # Project documentation (you are here)
```

---

## ⚙️ Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/<your‑org>/regional‑sales‑analytics.git
cd regional‑sales‑analytics

# 2. Create and activate a virtual env (optional but recommended)
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# 3. Install required packages
pip install -r requirements.txt

# 4. Run notebooks
jupyter lab
```

> **Tip:** The notebooks are sequential—run *cleaning-&-wrangling* first, then *EDA*.

---

## 📊 Power BI Dashboard

Open `dashboard/SALES REPORT.pbix` with Power BI Desktop.  
Key insights available:

| Page | What you’ll see |
|------|-----------------|
| **Executive Overview** | KPIs (Total Revenue, YoY Growth, Avg Order Value) |
| **Regional Drill‑down** | Interactive map & tables to compare regions |
| **Product Performance** | Top products, category trends, seasonality heatmap |
| **Customer Insights** | Segment analysis: new vs returning, CLV buckets |

---

## 📝 Methodology

1. **Data Cleaning**: standardized column names, fixed data types, removed duplicates, handled missing values with domain‑aware imputation.
2. **Feature Engineering**: created `OrderMonth`, `GrossMargin`, and regional profit ratios.
3. **Exploratory Analysis**: visualized sales trends, outliers, and correlations.
4. **Dashboard Design**: followed IBCS principles—consistent colors & layout, minimal clutter.

---

## 🔧 Dependencies

The core analysis relies on:

- `pandas`, `numpy`, `openpyxl`
- `matplotlib`, `seaborn`
- `jupyter`
- `powerbiclient` (optional: embed PBIX in notebooks)

See **requirements.txt** for the full list.

---

## 🗄️ Data Source

> **Regional Sales Dataset.xlsx**  
Synthetic but realistic multi‑region retail sales covering **2019‑2024**.  
All data is anonymized and safe for public use.

---

## 🤝 Contributing

Pull requests are welcome! Please:

1. Fork the repo
2. Create your feature branch (`git checkout -b feat/awesome`)
3. Commit changes (`git commit -m "Add awesome feature"`)
4. Push to the branch (`git push origin feat/awesome`)
5. Open a PR

---

## 📜 License

Distributed under the **MIT License**.  
See `LICENSE` for more information.

---

> Made with 💡 & 📈 by Khalil Benhammou
