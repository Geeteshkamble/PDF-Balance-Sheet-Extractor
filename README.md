# PDF Balance Sheet Extractor

This project extracts balance sheet data from a PDF file and saves it to a CSV file. Using `pdfplumber`, it reads text from each page in a specified PDF and employs regular expressions to identify key financial parameters. The extracted data is then stored in a structured CSV format for further analysis.

## Features

- Extracts balance sheet data, including:
  - Equity Capital
  - Reserves
  - Borrowings
  - Other Liabilities
  - Total Liabilities
  - Fixed Assets
  - Capital Work in Progress
  - Investments
  - Other Assets
  - Total Assets
- Saves extracted data to a specified CSV file.

## Prerequisites

- Python 3.x
- Required Libraries:
  - `pdfplumber`
  - `re`
  - `pandas`

## Usage

1. Set the path to the PDF file (`pdf_path`) containing the balance sheet data.
2. Set the path for the output CSV file (`csv_output_path`).
3. Run the notebook cells to extract and save data to the CSV file.

## Code Structure

- **Step 1:** Load the PDF and extract its text.
- **Step 2:** Use regular expressions to find and capture relevant financial parameters.
- **Step 3:** Save the extracted data to a CSV file.

## Example

An example run creates a CSV file with columns for "Parameter" and "Value", containing all identified parameters and their extracted values.
