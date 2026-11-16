# Gikomba Stall Sales & Stock Analysis

**Analyst:** Owen Sichere  
**Cohort:** 1 Million Devs Cohort  
**Repository:** `plp-da-a1-gikomba-stall-analysis`

## Business Problem

Wanjiku operates a fresh-produce stall at Gikomba Market and has tracked two weeks of daily sales (in KES) alongside rough inventory counts, reorder thresholds, unit costs, and selling prices. Without structured analysis, she lacks visibility into whether her revenue is growing week over week, which days drive or drag down cash flow, and which produce items risk running out of stock or yield the highest profit margins. Using core Python only (no `pandas` or `numpy`), this analysis transforms her raw ledger into an actionable performance report and restocking plan.

## How to Run

Open and run the notebook directly in Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/owenjuniour-max/plp-da-a1-gikomba-stall-analysis/blob/main/stall_analysis.ipynb)

Alternatively, clone this repository and open `stall_analysis.ipynb` in Jupyter Notebook or JupyterLab, then select **Kernel → Restart & Run All**.

## Top Three Findings

1. **Strong Week-on-Week Growth (+10.66%):** Revenue grew from **KES 22,050** in Week 1 to **KES 24,400** in Week 2 (a **KES 2,350** increase), bringing total 14-day sales to **KES 46,450** at a daily average of **KES 3,317.86**.
2. **Weekend Demand Surges +82.50% Above Weekdays:** Weekend sales average **KES 4,900.00/day** (peaking at **KES 5,600** on Week 2 Saturday) compared to **KES 2,685.00/day** on weekdays, with all **6 Weak days** (>20% below average, lowest **KES 1,950** on Week 1 Tuesday) occurring on Mon/Tue/Thu.
3. **Immediate Stockouts Loom on High-Margin Produce:** **Tomatoes** (18 kg vs. 25 kg reorder level; **33.33%** margin) and **Sukuma** (9 kg vs. 15 kg reorder level; **40.00%** margin) require urgent restocking, while **Avocado** delivers the highest gross margin at **42.86%** with only 2 kg buffer above its 10 kg reorder point.
