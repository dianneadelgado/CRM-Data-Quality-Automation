CRM Data Quality Automation

## Project Overview

CRM Data Quality Automation is an AI-powered workflow that cleans, validates, standardizes, and deduplicates business data using a combination of rule-based processing and local Large Language Models (LLMs).

The workflow helps organizations improve data quality before importing records into CRM, ERP, analytics, and reporting systems.

The solution reduces manual spreadsheet cleanup, minimizes human error, and ensures that business data remains accurate and consistent.

---

## Key Benefits

* Remove duplicate records automatically
* Standardize customer, supplier, and company names
* Validate required fields before import
* Improve CRM and operational data quality
* Generate automated cleaning reports
* Send execution summaries via email
* Run entirely on local AI using Ollama

---

## Problem Statement

Many organizations still manage leads, customers, vendors, and operational records using spreadsheets.

As datasets grow, data quality issues become increasingly common:

* Duplicate records
* Missing information
* Inconsistent formatting
* Human data-entry errors
* Time-consuming manual cleanup

Poor data quality impacts reporting accuracy, sales performance, customer management, and business operations.

CRM Data Quality Automation addresses these challenges by automatically cleaning and standardizing data before it enters downstream systems.

---

## Workflow Architecture

```text
Read Spreadsheet
        │
        ▼
Pre-Clean & Validate
        │
        ▼
Check Valid Rows
        │
        ▼
Batch Processing
        │
        ▼
AI Data Normalization
        │
        ▼
Deduplication
        │
        ▼
Write Clean Data
        │
        ▼
Generate Summary
        │
        ▼
Email Report
```

## AI Capabilities

The Hermes model is used to:

* Standardize customer and company names
* Normalize text formatting
* Improve data consistency
* Detect data quality issues
* Assist with record validation
* Prepare records for downstream business systems

The AI layer complements traditional rule-based validation, creating a hybrid approach that is both scalable and practical for real-world business data.

---

## Workflow Components

### 1. Read Spreadsheet

Imports raw records from Google Sheets.

### 2. Pre-Clean & Validate

Performs rule-based validation:

* Remove empty rows
* Validate required fields
* Identify invalid records
* Track processing statistics

### 3. Check Valid Rows

Determines whether sufficient valid records exist for processing.

### 4. Batch Processing

Splits large datasets into manageable batches to improve AI performance and scalability.

### 5. AI Data Normalization

Uses Hermes through Ollama to:

* Normalize text values
* Standardize naming conventions
* Improve record consistency

### 6. Deduplication

Removes duplicate records before final export.

### 7. Write Clean Data

Exports cleaned records into a destination spreadsheet.

### 8. Generate Summary

Creates execution metrics including:

* Total records processed
* Valid records
* Invalid records
* Duplicate records removed
* Final records exported

### 9. Email Report

Automatically sends processing results and execution summaries to stakeholders.

---

## Results

The workflow automatically:

* Validates incoming records
* Removes duplicate entries
* Standardizes formatting
* Produces clean output datasets
* Generates execution summaries
* Sends automated email notifications

This significantly reduces manual data-cleaning effort while improving overall data quality and operational efficiency.

---

## Why I Built This

This project was developed as a portfolio case study to demonstrate:

* AI Workflow Engineering
* Business Process Automation
* Local LLM Integration
* Data Quality Management
* Practical n8n Development
* Real-World Business Problem Solving

The goal was to showcase how AI can automate repetitive operational tasks while improving the quality and reliability of business data.

---

## Author

### Dianne Delgado

Engineer focused on building AI-powered business automation systems that streamline operations, improve data quality, and reduce manual work.
