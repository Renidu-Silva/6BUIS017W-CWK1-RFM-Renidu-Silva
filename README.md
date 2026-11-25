# 6BUIS017W-CWK1-RFM-Renidu-Silva
# Market Analysis and Stock Segmentation Using RFM

Individual coursework, CRM & CM With Business Intelligence, University of Westminster.

## Contents
- `CWK1_RFM_Analysis.ipynb`: Google Colab notebook with all code and outputs (Tasks 1 to 3).
- `data.zip`: data snapshot used for the reported results (S&P 500 list from Wikipedia and
  Yahoo Finance prices, volumes, splits and dividends, retrieved 18 November 2026; study period
  1 January 2021 to 1 January 2025, end date exclusive).
- `feature_table.csv`: one row per included share (486 shares) with the five features and the
  four cluster assignments.
- `inclusion_exclusion_log.csv`: every ticker and the reason for any exclusion.
- `fig_*.png`: figures used in the report.

## How to reproduce the results
1. Open `CWK1_RFM_Analysis.ipynb` in Google Colab.
2. Download `data.zip` from this repository and upload it to the Colab Files panel (do not unzip it).
3. Select Runtime → Run all.
4. The notebook prints "Using saved data snapshot: True" and loads the 18 November 2026 snapshot.
   Without `data.zip`, it downloads the data live, and results may differ slightly.

Random seed: 42. Observation date: 31 December 2024.
