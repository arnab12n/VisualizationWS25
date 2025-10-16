## Hospitality Data Visualization (Matplotlib + Seaborn)

This repository contains two self-contained Jupyter notebooks that highlights core and intermediate data visualization techniques on hospitality domain.  One can learn how to visualize trends, distributions, and relationships, and finally how to build a small insights dashboard.

### Notebooks
- `hospitality-data-visualization-matplotlib-basics.ipynb`
  - Introduction to data visualization with Matplotlib
  - Line, bar, pie, and scatter plots using hotel bookings data
  - KPI visuals: Occupancy Rate, ADR, and RevPAR with simulated data

- `seaborn-basics-and-dashboard-hospitality.ipynb`
  - Seaborn basics (line, bar, scatter) and intermediate plots (histplot, kdeplot, pairplot, jointplot, heatmap, boxplot)
  - Mini dashboard: revenue distribution, monthly comparisons, ADR vs rating, and correlation heatmap

Both notebooks generate synthetic datasets directly in the notebook, so no external data files are required.

### Prerequisites
- Python 3.11+
- Recommended: a virtual environment

### Quick Start (Windows PowerShell)
1. Create and activate a virtual environment (optional but recommended):
   ```powershell
   python -m venv venv
   .\venv\Scripts\Activate.ps1
   ```
2. Install dependencies:
   ```powershell
   pip install jupyter matplotlib==3.10.7 seaborn==0.13.2 pandas==2.3.3 numpy==2.3.4
   ```
3. Launch Jupyter and open the notebooks:
   ```powershell
   jupyter notebook
   ```
   Then navigate to:
   - `hospitality-data-visualization-matplotlib-basics.ipynb`
   - `seaborn-basics-and-dashboard-hospitality.ipynb`

### What can be Learned
- Matplotlib fundamentals: styling, grids, markers, line styles
- Seaborn conveniences: theme, palettes, statistical plots
- Hospitality KPIs: Occupancy Rate, ADR, RevPAR
- Interpreting visuals to derive business insights

### Reproducibility Notes
- The notebooks seed randomness (where used) for repeatable examples.
- Plots are generated from in-notebook synthetic data; runs offline.

### Contributing
Issues and suggestions are welcome. Feel free to open an issue or PR with improvements (e.g., adding more charts, real datasets, or explanations).




