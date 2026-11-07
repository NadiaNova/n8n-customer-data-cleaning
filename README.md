# 🤖 Automated Customer Data Cleaning Using n8n
###  • Data Cleaning Tool • Summary Report • Clean Dataset

Automated customer data cleaning using n8n, JavaScript, and Excel or, Clean a Messy Excel File Using n8n.

<p align="left">
  <img src="https://img.shields.io/badge/n8n-3776AB?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/Docker-FF4B4B?style=for-the-badge&logo=Docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/JavaScript-1C3C3C?style=for-the-badge&logo=JavaScript&logoColor=white" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Microsoft Excel-5B4BDB?style=for-the-badge" alt="Microsoft Excel" />
</p>

---

## Project Overview

This project demonstrates an automated customer data cleaning workflow built with n8n.

The workflow processes a messy Excel dataset, validates customer information, removes duplicate records, standardizes data, and exports a cleaned Excel file.

## Technologies Used

- n8n
- Docker
- JavaScript
- Microsoft Excel
- Regular Expressions

## Features

- Read customer data from Excel
- Remove empty rows
- Trim unnecessary spaces
- Standardize names and city names
- Validate email addresses
- Validate Bangladeshi mobile numbers
- Standardize date formats
- Remove duplicate customers
- Generate unique customer IDs
- Export cleaned Excel data
- Generate a data cleaning summary report

## Workflow Architecture

Manual Trigger
    |
Read Excel File
    |
Extract Spreadsheet Rows
    |
Clean Data (JavaScript)
    |
Convert to Excel
    |
Save Clean Excel File


![n8n Workflow](Workflow%20Architecture.png)

## Project Files

| File | Description |
|---|---|
| messy_customers.xlsx | Original input dataset |
| clean_customers.xlsx | Cleaned output dataset |
| Clean a Messy Excel File Using n8n.json | n8n workflow export |
| summary_report.txt | Cleaning summary |
| workflow-Clean a Messy Excel File Using n8n.jpg | Workflow screenshot |
| Demo MP4 | Workflow demonstration |

## How to Use

1. Import the workflow JSON into n8n.
2. Configure the input Excel file path.
3. Configure the output Excel file path.
4. Execute the workflow.
5. Check the cleaned Excel file and summary report.

## Execution Environment

- Windows
- Docker
- n8n running locally

## Workflow Screenshot

![n8n Workflow](workflow-Clean%20a%20Messy%20Excel%20File%20Using%20n8n.jpg)

## Demo Video

Watch the complete workflow execution demonstration.

## Learning Outcomes

This project demonstrates workflow automation, data validation, JavaScript-based data transformation, duplicate detection, and Excel file processing using n8n.

## Author

Afsana Nadia
