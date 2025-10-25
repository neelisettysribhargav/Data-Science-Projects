# Restaurant Data Analysis

Purpose
-------
This project demonstrates a staged data science workflow for restaurant-related data: exploration, feature engineering, and predictive modeling. Notebooks are organized by stage to make the pipeline easy to follow and reproduce.

Contents
--------
- `Level1_Data_Exploration.ipynb` — Data overview, cleaning, and initial visualizations.
- `Level2_Feature_Engineering.ipynb` — Creation and validation of predictive features.
- `Level3_Predictive_Modeling.ipynb` — Model training, evaluation, and interpretation.
- `datasets/Dataset .csv` — Source dataset (clean or inspect before reuse).

How to run
----------
1. Create and activate a virtual environment:
	```powershell
	python -m venv .venv
	.\.venv\Scripts\Activate.ps1
	pip install -r requirements.txt
	```
2. Run notebooks in order: Level1 → Level2 → Level3.

Notes & suggestions
-------------------
- Keep preprocessing steps in Level2 reproducible (wrap transformations in functions or a pipeline).
- Add tests for data transformations and a script to run the full pipeline end-to-end.

