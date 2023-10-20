# SIH Hospital Admissions Analysis

This repository contains a Python notebook that analyzes data from the Hospital Information System (SIH) of DATASUS. The primary focus is on the `{COLUMN_NAME}` column, which in our example indicates the cause of death. The analysis is based on data for the state of `{STATE_NAME}` during `{MONTH_YEAR}`.

## 📌 Overview

- **Dataset**: Hospital Information System (SIH) of DATASUS
- **Focus**: `CID_MORTE` column (Description: cause of death)
- **Region**: State of `{STATE_NAME}`
- **Time Period**: `{MONTH_YEAR}`

## 🛠 Prerequisites

- Python 3.x
- Jupyter Notebook (if you wish to run the `.ipynb` file)

## 📦 Dependencies

- `pysus`: For downloading SIH data
- `numpy`: For data manipulation
- `plotly`: For data visualization

You can install these dependencies using `pip`:

```bash
pip install pysus numpy plotly
