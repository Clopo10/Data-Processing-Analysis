# Data-Processing-Analysis

A small data cleaning and analysis project using the Telco Customer Churn dataset. This repository demonstrates data cleaning, exploratory data analysis, and produces a cleaned dataset and a Jupyter analysis notebook with findings.

**Project goals**

- Produce a clean CSV ready for modeling and analysis (`deliverables/cleaned_dataset.csv`).
- Document findings and code in `deliverables/data_analysis.ipynb`.

**Repository structure**

- **data/**: Original raw dataset(s). Example: [data/Telco-Customer-Churn.csv](data/Telco-Customer-Churn.csv)
- **deliverables/**: Processed outputs and the analysis notebook. See [deliverables/data_analysis.ipynb](deliverables/data_analysis.ipynb) and [deliverables/cleaned_dataset.csv](deliverables/cleaned_dataset.csv)
- `requirements.txt`: Python dependencies for reproducing the analysis.
- `README.md`: This file.

**Dataset**
The project uses `Telco-Customer-Churn.csv` (placed in `data/`). The notebook documents assumptions, cleaning steps, and exploratory plots used to understand churn drivers.

Prerequisites

- Python 3.8+ (recommended)
- `pip` available

Quick start

1. Create and activate a virtual environment (Windows PowerShell):

```powershell
python -m venv .venv
venv\Scripts\activate
pip install -r requirements.txt
```

2. Open and run the analysis notebook:

```powershell
jupyter notebook deliverables/data_analysis.ipynb
```

3. The cleaned dataset produced by the notebook is saved to `deliverables/cleaned_dataset.csv`.

Reproducing results

- Run all cells in `deliverables/data_analysis.ipynb`. The notebook contains the data-loading and cleaning pipeline; running it end-to-end will regenerate `deliverables/cleaned_dataset.csv`.
