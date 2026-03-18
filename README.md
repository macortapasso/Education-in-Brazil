# Education-in-Brazil

Exploratory data analysis and correlation analysis of Brazil's PISA performance.

## Repository contents

- `Brazilian_Education.ipynb`: main notebook with the analysis and narrative.
- `EdStatsCountry.csv`, `EdStatsCountry-Series.csv`, `EdStatsSeries.csv`, `EdStatsFootNote.csv`: supporting files from the World Bank Education Statistics dataset.

## Data requirement

The main file `EdStatsData.csv` is not stored in this repository because of its size. To run the notebook, download `EdStatsData.csv` from the World Bank Education Statistics source referenced in the notebook and place it in one of these locations:

1. the project root, or
2. the parent directory of the project.

The notebook now raises a clear error if the file is missing.

## Notebook rendering

The notebook is intended to be viewed in Jupyter or JupyterLab. Plotly charts are configured to render locally in the notebook, so no Plotly account or API key is required.

## HTML view

You can also inspect the notebook through nbviewer:
https://nbviewer.jupyter.org/github/macortapasso/Education-in-Brazil/blob/master/Brazilian_Education.ipynb
