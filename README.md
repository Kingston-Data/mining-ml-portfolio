# Mining ML Portfolio

Machine learning projects focused on predictive maintenance and data analysis for the mining industry.

---

## About
This repository contains hands-on ML projects built around real-world mining industry use cases —
including equipment failure prediction, sensor data analysis, and anomaly detection.

Tools used: Python, pandas, numpy, matplotlib, scikit-learn, Jupyter Notebook

---

## Structure

mining-ml-portfolio/

│

├── week1-eda/

│   └── deepmine_week1_eda.ipynb

│

└── README.md

---

## Projects

###  Week 1 — Exploratory Data Analysis (EDA)
**Notebook:** `week1-eda/deepmine_week1_eda.ipynb`  
**Dataset:** AI4I 2020 Predictive Maintenance Dataset (10,000 machine sensor records)

**What I did:**
- Inspected dataset structure — 14 columns, zero missing values
- Analysed machine failure rate using `value_counts()`
- Compared average air and process temperature for failed vs non-failed machines
- Plotted torque distribution using a histogram
- Broke down failures by type (Tool Wear, Heat Dissipation, Power Failure, Overstrain, Random)

**Key findings:**
- Overall failure rate: **3.39%** — heavily imbalanced dataset
- Failed machines run hotter in both air temp (~+0.9K) and process temp (~+0.3K)
- Heat Dissipation is the most common failure type (115 cases)
- Random failure is the least common (19 cases)
- Class imbalance must be handled carefully when building ML models

---

## Dataset

AI4I 2020 Predictive Maintenance Dataset  
Source: https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset

> **Note:** Dataset files are not included in this repository.  
> Download `ai4i2020.csv` and place it inside the `week1-eda/` folder before running the notebook.

---