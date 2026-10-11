# Python ETL Pipeline

A simple ETL pipeline built with Python and Pandas to extract, transform, and load data from multiple file formats.

## Features
- **Extract:** Read data from CSV, JSON, and XML files.
- **Transform:** Convert height from inches to meters and weight from pounds to kilograms.
- **Load:** Save transformed data to a CSV file.
- **Logging:** Track ETL execution steps and progress.

## Project Structure
```text
python-etl-pipeline/
├── data/                  # Input files
├── etl_pipeline.py        # Main ETL script
├── transformed_data.csv   # Output file
├── log_file.txt           # Execution logs
└── README.md
```

## Requirements
- Python 3
- Pandas

Install Pandas:
```bash
pip install pandas
```

## Usage
1. Place the input CSV, JSON, and XML files in the `data/` directory.
2. Run the pipeline:
   ```bash
   python etl_pipeline.py
   ```
3. Find the transformed data in `transformed_data.csv`.

## Technologies
Python · Pandas · XML · JSON · CSV
