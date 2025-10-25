# Hotel Booking Analysis

Purpose
-------
Analyze hotel booking patterns, cancellation behavior, and features that influence bookings and cancellations. The notebook demonstrates EDA, feature engineering, and modeling approaches for cancellation prediction.

Contents
--------
- `Hotel_Booking_Analysis.ipynb` — Complete analysis of booking data and suggested modeling approaches.
- `datasets/hotel_booking.csv` — Dataset used for analysis.

How to run
----------
1. Create and activate a virtual environment and install dependencies:
	```powershell
	python -m venv .venv
	.\.venv\Scripts\Activate.ps1
	pip install -r requirements.txt
	```
2. Start Jupyter and open the notebook.

Notes & suggestions
-------------------
- Consider training a classification model for cancellations and include calibration/ROC analysis.
- Add feature importance plots and an exportable prediction script for downstream use.

