# Web Scraping Examples

Purpose
-------
Demonstrate practical web scraping patterns and basic data cleaning. The notebooks show how to fetch pages, parse content, and save cleaned datasets for downstream analysis.

Contents
--------
- `Web_Scraping(1).ipynb` — Basic scraping examples using `requests` and BeautifulSoup.
- `Web_Scraping(2).ipynb` — More advanced examples (pagination, rate limiting, basic politeness strategies).
- `datasets/cars.csv`, `datasets/data.csv` — Sample outputs from scraping notebooks.

How to run
----------
1. Create and activate a virtual environment:
	```powershell
	python -m venv .venv
	.\.venv\Scripts\Activate.ps1
	pip install requests beautifulsoup4 pandas jupyter
	```
2. Start Jupyter and open the notebooks.

Ethics and legality
-------------------
- Only scrape websites that permit crawling in their `robots.txt` or where you have explicit permission.
- Respect rate limits, add delays between requests, and avoid overloading remote servers.

Suggested improvements
----------------------
- Wrap scrapers into small scripts with logging and retry logic.
- Store results in a structured format (Parquet or SQLite) for reproducibility.

