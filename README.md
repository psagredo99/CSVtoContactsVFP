# CSV to Salesforce Contact Upsert (ES language)

A Salesforce Apex class and Visualforce page for upserting contact records from a CSV file based on the external id field.

By: Pablo Sagredo

<a href="https://githubsfdeploy.herokuapp.com?owner=psagredo99&repo=CSVtoContactsVFP&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

## Description
This repository contains both an Apex class and a Visualforce page designed to process and insert data from a CSV file into Salesforce Contact objects. It includes methods for reading CSV files, validating and transforming data, inserting records, and displaying the results.

## Features

- Upload CSV files and validate them before insertion.
- Able to auto map the fields
- Handle various field types, including dates, datetimes, booleans, and textareas.
- Display detailed messages about the insertion process.
- Utilizes the external id field for upserting records.
- 

## Usage

-Upload CSV:

![image](https://github.com/psagredo99/CSVtoContactsVFP/assets/72439144/386f1116-fe7f-4a08-af20-50cf07ce39cb)


-CSV is uploaded and validated:

![image](https://github.com/psagredo99/CSVtoContactsVFP/assets/72439144/1031125e-4b0b-4929-b2f0-aa39fc39f524)

-Result (Inserted + Updated):

![image](https://github.com/psagredo99/CSVtoContactsVFP/assets/72439144/fd6773cd-7042-4f8b-8583-86e98d8c5f2c)




### Clone or Download

Clone the repository to your local machine using Git:

```bash
git clone [repository URL]
