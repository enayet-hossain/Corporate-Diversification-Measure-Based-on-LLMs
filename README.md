# Corporate Diversification Measure Dataset

This repository hosts the dataset introduced in:

> Hossain, M. E., & Hossain, K. T. (2025). Corporate Diversification and 10-K Narratives: A Novel Approach Using Large Language Models. *Borsa Istanbul Review*.

## 📄Description
This dataset provides a new measure of corporate diversification based on the textual analysis of business segment descriptions in firms’ 10-K filings. The measure captures the differences between business segments using computational linguistics rather than SIC codes.

## 📂 Contents
- `data/corporate_diversification_measure.csv` – Full dataset containing firm-year level diversification scores.

## 🛠 Methodology
The measure is developed by:
1. Extracting business segment names from the Compustat Historical Segment Database.
2. Calculating a dissimilarity score between business segments at the firm-level using text embeddings extracted from an LLM.

For the complete methodology, you can read the full paper [**here**] (https://doi.org/10.1016/j.bir.2025.08.002). 

## 📅 Coverage
- **Period:** 1990–2023
- **Firms:** Public U.S. companies filing 10-K reports.

## 📚 Citation
If you use this dataset, please cite:

Hossain, M. E., & Hossain, K. T. (2025). Corporate Diversification and 10-K Narratives: A Novel Approach Using Large Language Models. Borsa Istanbul Review.
