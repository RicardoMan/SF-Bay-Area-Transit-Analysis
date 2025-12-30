# SF-Bay-Area-Transit-Analysis
## Data Source This analysis uses publicly available GPS data from [511.org](https://511.org/open-data/transit),  the official Bay Area transit information system operated by the Metropolitan Transportation Commission.  Data is available under their Terms of Service for research and analysis.


# SF Bay Area Transit Efficiency Analysis

## Overview
Analysis of 2.17M GPS records from SF Muni and AC Transit revealing $1.38M in daily operational waste.

## Key Findings
- **Daily waste:** $1,383,687
- **Idle time:** 61% (vs 25% baseline)
- **Annual projection:** $348.7M
- **ML accuracy:** 81.5%

##  Tech Stack
- Python (pandas, scikit-learn, XGBoost)
- SQLite
- Kepler.gl
- LaTeX

##  Files
- `analysis.ipynb` - Full Jupyter notebook
- `report.pdf` - Technical report
- `data/` - Data collection scripts
- `viz/` - Visualizations

## Data Source
[511.org](https://511.org/open-data/transit) - Bay Area public transit API

## Run Analysis
```bash
pip install -r requirements.txt
python collect_data.py
jupyter notebook analysis.ipynb
```


