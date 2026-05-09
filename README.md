# Phishing Website Detection (ML)

## Overview

This project was completed for the CSE427 (Machine Learning) course and builds a phishing URL classifier using engineered URL and HTML features. The notebook covers exploratory data analysis, feature selection, model comparison, ensemble voting, and robust evaluation.

## Project Structure

- cse424_project.ipynb
- phishing.csv
- requirements.txt

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

Open cse424_project.ipynb in Jupyter or VS Code and run all cells.

## Notes

- Feature extraction uses live network requests, so results can vary over time.
- Random seed used where applicable: 42.
