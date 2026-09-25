# Personal Activity Intelligence Report

This project analyses a personal daily activity log for the CAP776 **My Data, My Story** assignment.

## Contents

- `main.py` — reads the Excel log, validates records, calculates activity indices, and prints the analysis report.
- `12603926.xlsx` — the daily activity dataset.
- `report.txt` — generated project report/output.

## Dataset period

The dataset records daily activity information from **13 August 2026 through today**. The Python program calculates the expected number of days dynamically, checks for duplicate or out-of-range dates, and reports any missing daily entries. It includes sleep, fitness, study, coding, class time, other activities, mood, satisfaction, and energy levels.

## Requirements

```bash
pip install openpyxl
```

## Run

```bash
python main.py
```

Keep the Excel file in the same directory as `main.py` before running the program.
