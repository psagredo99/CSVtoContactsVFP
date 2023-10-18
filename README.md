# CSV to Salesforce Contact Upsert (ES language)

A Salesforce Apex class and Visualforce page for upserting contact records from a CSV file based on the external id field.

By: Pablo Sagredo
## Description

This repository contains both an Apex class and a Visualforce page designed to process and insert data from a CSV file into Salesforce Contact objects. It includes methods for reading CSV files, validating and transforming data, inserting records, and displaying the results.

## Features

- Upload CSV files and validate them before insertion.
- Able to auto map the fields
- Handle various field types, including dates, datetimes, booleans, and textareas.
- Display detailed messages about the insertion process.
- Utilizes the external id field for upserting records.

## Getting Started

To use the Apex class and Visualforce page, follow these steps:

1. [Clone or Download](#clone-or-download) the repository.
2. [Deploy to Salesforce](#deploy-to-salesforce) using Salesforce Workbench or other deployment tools.
3. [Access the Visualforce Page](#access-the-visualforce-page) to interact with the class.

### Clone or Download

Clone the repository to your local machine using Git:

```bash
git clone [repository URL]
