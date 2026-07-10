# Indian Banking Sector - MIS Supervisory Dashboard (RBI Data)

**Tools:** Python, SQL, Pandas, Scipy, Scikit-learn, Matplotlib, Seaborn

## Overview
End-to-end MIS supervisory analysis of Indian scheduled commercial banks using real RBI published data (2005–2025), covering NPA movement, earnings trends, write-off analysis, and recovery rate forecasting across 146 banks.

## Key Findings
- Gross NPA peaked at ₹18.5 lakh crore in 2018 - the worst banking stress period in India's post-liberalisation history
- NPA additions correlated positively with total income growth (r=0.55, p<0.01) - systemic stress scaled with sector growth
- NPA/Income ratio averaged 56.28% during 2016–2020 vs 32.12% post-2021 - significant sector recovery
- No statistically significant difference in NPA ratios pre vs post 2018 peak (p=0.19) - stress persisted
- Forecasted NPA recovery rate of 43.72% for 2026 based on trend analysis

## Data Source
Reserve Bank of India - Statistical Tables Relating to Banks in India (2005–2025)
Publicly available at: https://www.rbi.org.in

## Project Structure
- `rbi_mis_analysis.ipynb` - full analysis notebook
- `rbi_mis_dashboard.png` - MIS supervisory dashboard
- `rbi_statistical_analysis.png` - statistical analysis results
