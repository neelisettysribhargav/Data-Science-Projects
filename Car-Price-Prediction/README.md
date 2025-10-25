# Car Price Prediction

Purpose
-------
Predict the selling price of used cars using available listing attributes. The notebooks in this folder demonstrate data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

Contents
--------
- `Car_Price_Prediction.ipynb` — End-to-end pipeline: data cleaning, EDA, feature engineering, modeling (linear and tree-based models), and evaluation.
- `Car_Price_Prediction(1).ipynb` — Variant/alternate analysis; consider consolidating into a single canonical notebook.
- `datasets/Car details v3.csv`, `datasets/cardata.csv` — Source data files used by the notebooks.

How to run
----------
1. From the repository root, create and activate a virtual environment:
	```powershell
	python -m venv .venv
	.\.venv\Scripts\Activate.ps1
	pip install -r requirements.txt
	```
2. Start Jupyter Lab or Notebook:
	```powershell
	jupyter lab
	```
3. Open `Car_Price_Prediction.ipynb` and run cells sequentially.

Notes & suggestions
-------------------
- Record the final model and preprocessing steps so predictions can be reproduced (save a `model.joblib` or similar).
- Consolidate duplicate notebooks and keep one canonical analysis file.
- Consider adding a small prediction script (`predict.py`) that loads the trained model and accepts inputs.

Dependencies (typical)
----------------------
pandas, numpy, scikit-learn, matplotlib, seaborn, joblib, jupyter

