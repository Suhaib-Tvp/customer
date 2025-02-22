# Customer Data Cleaning Script

## Overview
This Python script processes and cleans a customer dataset stored in a CSV file. It identifies and fixes issues such as missing values, invalid data, and formatting inconsistencies, ensuring the dataset is standardized and ready for analysis.

## Features
- Identifies missing values, invalid emails, and duplicate records.
- Handles missing values by filling them with default values or computed averages.
- Fixes invalid data such as negative ages and incorrect email formats.
- Standardizes phone numbers and country names.
- Detects and removes duplicate records.
- Identifies outliers in purchase amounts.
- Saves the cleaned data to a new CSV file.

## Requirements
- Python 3.x
- Pandas Library (`pip install pandas`)
- Regular Expressions (built-in `re` module)

## Installation
1. Install Python if not already installed.
2. Install required dependencies using:
   ```sh
   pip install pandas
   ```

## Usage
1. Place the dataset (`customers.csv`) in the script directory or update the path accordingly.
2. Run the script using:
   ```sh
   python process_customer.py
   ```
3. The cleaned data will be saved as `customers_cleaned.csv`.

## Output
- The script prints the number of issues before and after cleaning.
- The cleaned dataset is saved as `customers_cleaned.csv`.

## Evaluation Criteria
- **Correctness:** Ensures all data issues are resolved properly.
- **Efficiency:** Uses Pandas optimally to handle missing data and transformations.
- **Data Integrity:** Maintains accuracy and consistency in cleaned data.
- **Code Readability:** Uses modular functions with clear comments and meaningful variable names.
- **Error Handling:** Handles unexpected input formats to prevent runtime errors.

## License
This project is open-source and can be modified as needed.


