# ATMS SHAP Tutorial

Graduate-level tutorial demonstrating **SHAP (Shapley values)** for explaining atmospheric ML models.

## Quickstart

```bash
mamba env create -f environment.yml
mamba activate atms-shap
jupyter lab
# open notebooks/ATMS_SHAP_Tutorial.ipynb
```

Or with pip:

```bash
python -m venv .venv && source .venv/bin/activate  # (on Windows use .venv\Scripts\activate)
pip install -r requirements.txt
jupyter lab
```

## Contents
- `notebooks/ATMS_SHAP_Tutorial.ipynb` — main tutorial
- `data/sample_heavyrain_features.csv` — small synthetic sample (optional)
- `environment.yml` / `requirements.txt` — dependencies

## License
MIT
