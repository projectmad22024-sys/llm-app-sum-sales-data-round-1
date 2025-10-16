# CSV Sales Sum Web Application

This simple webpage reads a CSV data embedded within the script, extracts the 'Sales' column, computes the total sum, and displays the result in a `<div>` with the ID 'total'.

## Features
- Contains all logic within a single HTML file.
- Parses CSV data without external libraries.
- Displays the total sales sum dynamically.

## How to use
1. Save the `index.html` file.
2. Open it in a web browser.
3. The total sum is displayed automatically.

## Note
- The provided sample CSV data does not include explicit 'Sales' values. The script injects sample sales values to demonstrate the calculation.

## Note on Data Integration
- To work with actual CSV file, replace the `csvData` string with fetched CSV data (e.g., via AJAX).