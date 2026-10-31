# n8n Sales Reporting Automation

## Project Overview

This project demonstrates a sales reporting workflow built with **n8n**, JavaScript and Google Sheets.

The workflow retrieves sample sales data from a GitHub CSV file, converts it into structured records, calculates key business metrics and automatically appends the final report to Google Sheets.

## Workflow Architecture

**Manual Trigger → HTTP Request → CSV Conversion → Sales Calculation → Google Sheets**

### Workflow Steps

1. **Manual Trigger:** Starts the workflow when manually executed.
2. **HTTP Request:** Downloads the sample sales CSV file from GitHub.
3. **CSV Conversion:** Converts CSV text into structured records using a JavaScript Code node.
4. **Sales Calculation:** Calculates total records, units sold, revenue, expenses and estimated profit.
5. **Google Sheets:** Appends the calculated report to a Google spreadsheet.

## Technologies Used

- n8n
- JavaScript
- HTTP Request
- CSV data processing
- Google Sheets
- GitHub

## Sample Output

The workflow was tested using five fictional sales records.

| Metric | Result |
|---|---:|
| Records Processed | 5 |
| Units Sold | 15 |
| Total Revenue | $449.85 |
| Total Expenses | $125.00 |
| Estimated Profit | $324.85 |

## Sample Data

The project includes a sample CSV file:

`sample-sales-data.csv`

All records are fictional and intended for demonstration purposes.

## Key Skills Demonstrated

- Workflow automation with n8n
- Data collection through HTTP requests
- CSV parsing and transformation
- JavaScript-based calculations
- Google Sheets integration
- Automated reporting workflow design

## Project Status

**Completed and tested:** The sample-data workflow successfully processes the CSV, calculates the reporting metrics and appends the result to Google Sheets.

This is a portfolio demonstration. It does not currently connect to live Shopify, Amazon, ClickBank or other sales accounts.

## Portfolio

GitHub Repository: https://github.com/sameagee/n8n-sales-reporting-workflow


