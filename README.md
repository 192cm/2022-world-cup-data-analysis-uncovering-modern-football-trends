<div align="center">

# ⚽ 2022 World Cup Football Trends Analysis

**Football analytics notebook** — Analyzes 2022 FIFA World Cup match statistics to compare team performance and playing patterns.

<br>

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/) [![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/) [![Pandas](https://img.shields.io/badge/Pandas-Data%20analysis-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/) [![scikit-learn](https://img.shields.io/badge/scikit--learn-Clustering-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/) [![License](https://img.shields.io/badge/License-Not%20specified-lightgrey?style=flat-square)](https://choosealicense.com/no-permission/)

<br>

[Features](#features) · [Quick Start](#quick-start) · [Usage](#usage) · [Architecture](#architecture) · [Dependencies](#dependencies) · [License](#license)

</div>

---

## ✨ Features

- **Match-level analysis** — Compares possession, goals, attempts, passes, line breaks, fouls, and defensive pressure across World Cup matches.
- **Team performance profiling** — Uses team-by-team statistics to identify attacking and defensive differences.
- **Visual exploration** — Builds charts with `matplotlib` and `seaborn` to make tactical patterns easier to inspect.
- **Feature scaling** — Applies `StandardScaler` and `MinMaxScaler` before model-based analysis.
- **Clustering workflow** — Uses `KMeans`, silhouette scoring, and UMAP to group teams or matches by statistical similarity.

---

## 🚀 Quick Start

### Environment setup

```bash
git clone https://github.com/kunho192/2022-world-cup-data-analysis-uncovering-modern-football-trends.git
cd 2022-world-cup-data-analysis-uncovering-modern-football-trends
python -m venv .venv
source .venv/bin/activate
pip install pandas numpy matplotlib seaborn scikit-learn umap-learn jupyter
```

### Credentials / config

```bash
echo "No API keys are required. Google Colab's free tier can run the notebook."
```

### Run

```bash
jupyter notebook 2022_world_cup_football_trends_analysis.ipynb
```

---

## 📖 Usage

### Jupyter Notebook

```bash
jupyter notebook 2022_world_cup_football_trends_analysis.ipynb
```

Run the notebook cells from top to bottom:

| Step | What happens |
|------|--------------|
| Import libraries | Loads data, visualization, preprocessing, clustering, and dimensionality-reduction packages |
| Load data | Reads the 2022 World Cup match statistics used in the analysis |
| Explore metrics | Inspects team and match variables such as possession, attempts, passes, fouls, and pressures |
| Visualize patterns | Creates charts for comparison and trend discovery |
| Cluster observations | Groups similar statistical profiles with scaled features |

> If you run the notebook outside Google Colab, update any Colab or Google Drive path in the data-loading cell to match your local dataset location.

---

## 🏗️ Architecture

```
2022-world-cup-data-analysis-uncovering-modern-football-trends/
├── 2022_world_cup_football_trends_analysis.ipynb  # analysis workflow
└── README.md                                      # project overview
```

```
World Cup match statistics
   │  loaded into a pandas DataFrame
   ▼
Data inspection and cleaning
   │  selected football performance metrics
   ▼
Exploratory visual analysis ──▶ charts and comparison views
   │  scaled numeric features
   ▼
KMeans and UMAP workflow ──▶ team or match similarity groups
   │  interpreted clusters
   ▼
Football trend insights
```

> The project keeps the full analysis in one notebook so the data preparation, visualization, and modeling steps remain readable in execution order.

---

## 📦 Dependencies

| Package | Role |
|---------|------|
| `pandas` | Loads and transforms tabular match data |
| `numpy` | Supports numeric operations |
| `matplotlib` | Builds base visualizations |
| `seaborn` | Builds statistical charts |
| `scikit-learn` | Scales features and runs clustering |
| `umap-learn` | Projects high-dimensional features for visual grouping |
| `jupyter` | Runs the notebook locally |

---

## 📄 License

No license file is included in this repository.
