# Excel Converter Utilities

This project contains two simple Python utility functions to convert Excel files into CSV and JSON formats using the `pandas` library.

## Features

- Convert `.xlsx` or `.xls` files to `.csv`
- Convert `.xlsx` or `.xls` files to `.json`
- Option to choose specific sheets
- Clean and readable output

## Requirements

Make sure you have the required libraries installed:

```bash
pip install pandas openpyxl

from your_module import excel_to_csv

excel_to_csv("input.xlsx", "output.csv")

from your_module import excel_to_json

excel_to_json("input.xlsx", "output.json")
