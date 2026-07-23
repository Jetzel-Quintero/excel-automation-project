# Project 1: Automated Data Cleaning with Power Query

## Overview

This project demonstrates how to automate the data cleaning process of a raw, unformatted sales dataset using **Power Query** in Microsoft Excel. Instead of manually fixing data every time, the pipeline handles errors and formatting changes instantly with a single click.

## Features & Transformations

- **Trim Whitespace:** Automatically cleaned extra leading and trailing spaces in customer names.
- **Error Handling:** Managed and filtered invalid text entries in numeric amount columns.
- **Date Standardization:** Unified mixed date formats into a standard, clean system date format.

## Directory Structure

- `data_raw/`: Contains the original unformatted CSV file (`sales_raw.csv`).
- `data_clean/`: Contains the final processed Excel workbook (`sales_cleaned.xlsx`).
