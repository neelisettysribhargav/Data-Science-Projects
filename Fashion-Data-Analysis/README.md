# Fashion Data Analysis

Purpose
-------
Analyze and visualize fashion-related datasets and survey responses. The notebooks contain exploratory data analysis (EDA), data cleaning steps, and visualizations designed to surface trends and customer preferences.

Contents
--------
- `Fashion_Data_Analysis.ipynb` — Main exploratory analysis and visualizations.
- `Fashion_Data_Analysis(1).ipynb` — Secondary/alternate analysis.
- `datasets/Fashion(Data Points) - Form responses 1.csv` — Survey/form responses.
- `datasets/fashion_data_2018_2022.xls` — Historical fashion dataset.

How to run
----------
1. Create and activate a virtual environment:
	```powershell
	python -m venv .venv
	.\.venv\Scripts\Activate.ps1
	pip install pandas numpy matplotlib seaborn openpyxl jupyter
	```
2. Start Jupyter and open `Fashion_Data_Analysis.ipynb`.

Notes & suggestions
-------------------
- Standardize and document column names in a data dictionary.
- Clean the survey CSV for inconsistent entries and missing values before analysis.
- If you plan to model outcomes, add a notebook that trains and evaluates simple classifiers/regressors.

