# Ionizable Lipid Prediction

Machine learning-based prediction and screening of ionizable lipid performance.

## Repository contents

| File | Description |
| --- | --- |
| ML_1.ipynb | Molecular descriptor calculation and feature preprocessing |
| ML_2.ipynb | Model training, evaluation, 2D screening, and 3D refinement |
| ML_3.ipynb | Feature correlation, SHAP analysis, and candidate visualization |
| ML_4.ipynb | Comparison of predicted and experimental results |
| Pre.csv | Input data for ML_4.ipynb |

## Workflow

The intended analysis order is:

1. ML_1.ipynb — generate molecular features.
2. ML_2.ipynb — train models and screen candidates.
3. ML_3.ipynb — interpret models and visualize candidates.

ML_4.ipynb analyzes Pre.csv separately.
Keep Pre.csv in the same working directory as ML_4.ipynb.

## Software dependencies

The notebooks use Python, Jupyter, NumPy, pandas, SciPy,
Matplotlib, seaborn, scikit-learn, RDKit, XGBoost,
LightGBM, SHAP, joblib, and tqdm.

Exact package versions and installation instructions
will be added after environment verification.

## Data availability and current status

This repository is a working version under preparation.

Full executionfrom a clean environment has not yet been verified.

## Publication and citation

Publication details and an archived release DOI will
be added when the publication version is finalized.
