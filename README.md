# ScoreMe Assignment

## Overview
This project extracts tabular data from bank statements in PDF format and saves it to Excel files. It uses pattern matching and text processing to identify transaction details, converting unstructured PDF content into structured tables.

## Author
- **Name**: Shiv Prakash Verma  
- **Institution**: IIT Ropar  
- **Roll No.**: 2021EEB1030  

## Features
- Extracts transaction data from various PDF bank statement formats  
- Identifies date, description, debit, credit, and balance information  
- Handles multiple table formats with different date patterns  
- Exports data to formatted Excel files with auto-adjusted column widths  
- Works with Google Colab for easy file upload and download  

## Usage
1. Upload a PDF bank statement  
2. The system will process and extract transaction tables  
3. Download the resulting Excel file with organized transaction data  

## Technical Details
- Uses `PyPDF2` for PDF text extraction  
- Implements regex pattern matching for data identification  
- Handles various date formats and transaction layouts  
- Organizes data using `pandas` DataFrames  
- Exports to Excel with `openpyxl`  
```
