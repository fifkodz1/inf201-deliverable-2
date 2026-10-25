# INF201 – Deliverable 2

This repository contains our solution for INF201 Deliverable 2: Campus Coffee Shop Sales Pipeline.

## Project description

The Jupyter notebook processes transaction logs stored in nested folders. The pipeline:

- discovers transaction files recursively;
- reads files with different text encodings;
- parses and cleans transaction records;
- excludes inactive cash registers;
- removes price outliers using NumPy;
- corrects NOK prices;
- sorts the cleaned transactions;
- generates the required CSV and JSON reports;
- validates the final results.

## Main files

- `deliverable_2.ipynb` – completed Jupyter notebook
- `INF201-Deliverable 2.pdf` – PDF version of the notebook
- `generate_data_for_d2.py` – input data generator
- `requirements.txt` – required Python packages
- `data/` – transaction data and configuration files

## Generated reports

- `cleaned_transactions.csv`
- `hourly_revenue.json`
- `item_refund_ratios.csv`
- `status_pivot_table.csv`

## How to run

1. Install the required packages:

   `python -m pip install -r requirements.txt`

2. Generate the input data:

   `python generate_data_for_d2.py`

3. Open `deliverable_2.ipynb` and run all cells from top to bottom.

A successful run ends with:

`All validation checks passed.`
