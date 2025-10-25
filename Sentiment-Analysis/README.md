# Sentiment Analysis

Purpose
-------
Explore natural language preprocessing techniques and build baseline sentiment classification models. Notebooks contain experiments with feature extraction, stopword removal, and model evaluation.

Contents
--------
- `Stopwords_Removal.ipynb` — Experiments on stopword removal and text cleaning.
- `Sentiment_Analysis(1).ipynb`, `Sentiment_Analysis(2).ipynb` — Modeling experiments using TF-IDF and traditional classifiers.
- `datasets/sentiment_analysis.csv`, `datasets/sentimentdataset.csv` — Labeled datasets used for training and evaluation.

How to run
----------
1. Create and activate a virtual environment and install dependencies:
	```powershell
	python -m venv .venv
	.\.venv\Scripts\Activate.ps1
	pip install -r requirements.txt
	```
2. If using NLTK, download required resources inside the environment:
	```python
	import nltk
	nltk.download('stopwords')
	```
3. Start Jupyter and run the notebooks.

Notes & suggestions
-------------------
- Add cross-validation and standardized evaluation metrics (precision/recall/F1 and confusion matrix).
- Consider experimenting with embeddings (Word2Vec, FastText) or transformer-based models when compute permits.

