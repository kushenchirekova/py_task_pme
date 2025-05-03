# py_task_pme


# Contract Features Extraction

This notebook parses JSON-formatted contract data and extracts structured features for analysis and modeling.

## Contents

- `contract_parser.ipynb`: main notebook that processes `data.csv`
- `contract_features.csv`: final dataset with extracted features
- `data.csv`: original dataset with contract JSON column
- `features.xlsx`: list of target features (if provided)

## Features Extracted

- Number of contracts
- Total and average contract amounts
- Number and sum of loans
- Unique bank count
- First claim date
- Last contract date

## Tools Used

- Python 3.13
- pandas
- json
