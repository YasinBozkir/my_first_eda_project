[![Shipping files](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml)

# King County Housing Market - EDA Project

## Client: Jennifer Montgomery
High-budget buyer looking for a waterfront property in King County.  
Goal: Buy within 1 month, resell within 1 year at maximum profit.

## Project Structure
├── data/               # Dataset (not uploaded to GitHub)
├── images/             # All visualizations
├── EDA.ipynb           # Main analysis notebook
├── column_names.md     # Column descriptions
└── requirements.txt    # Dependencies

## Research Questions & Hypotheses
| # | Question | Hypothesis | Result |
|---|----------|------------|--------|
| H1 | Does waterfront affect price? | Waterfront = higher price | ✅ 3.2x premium |
| H2a | Does grade affect price? | Higher grade = higher price | ✅ 0.67 correlation |
| H2b | Is Medina above county avg? | Medina prices > county avg | ✅ 4x above average |
| H3a | Does renovation affect price? | Recent renovation = higher price | ✅ Confirmed |
| H3b | Post-2000 reno vs never? | Post-2000 > never renovated | ✅ $301K premium |

## Key Recommendations
1. **Buy waterfront** — 3.2x price premium
2. **Target Medina (98039)** — most prestigious zip, 4x county average
3. **Prioritize grade 11+** — strong price correlation
4. **Recently renovated preferred** — $301K above never-renovated

## Requirements
- pyenv
- python==3.11.3

## Setup
```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```