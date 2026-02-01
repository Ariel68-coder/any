# Investment Analysis & AI Agent Project

This repository contains a Python/Jupyter-based investment analysis project that integrates
financial data collection, ratio analysis, valuation (DCF & multiples), risk assessment,
and LLM-assisted investment memo generation.

---

## 1. Project Structure

```text
.
├── 1.31.ipynb                # Main Jupyter Notebook (core analysis & results)
├── data/
│   ├── raw/                  # Raw financial data fetched from APIs (optional)
│   └── processed/            # Cleaned and processed datasets (optional)
├── outputs/
│   ├── figures/              # Generated charts and visualisations
│   └── memo/                 # Final investment memo (if exported)
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation (this file)
└── .env.example              # Example environment variable file (API keys)
