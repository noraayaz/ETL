# ETL Automation for Vehicle Data

Project Description

This Python script automates the ETL process for vehicle data stored in various file formats including CSV, JSON, and XML. The script extracts data from these files, transforms it to ensure data quality and consistency, and loads it into a CSV file for further use.

Key Features

*  Multi-Source Data Handling: Capable of extracting data from multiple file types: CSV, JSON, and XML.
*  Data Transformation: Includes data cleaning steps, specifically rounding prices to two decimal places.
*  Automated Logging: Logs the progress of each ETL phase to a text file, providing timestamps and status updates.

Technologies Used

*  Python 3
*  Pandas for data manipulation
*  xml.etree.ElementTree for XML file parsing
*  Glob for file handling

Files

*  log_file2.txt: Automatically generated log file that captures the progress of the ETL process.
*  transformed_data2.csv: The output file where the transformed data is stored.

Logging

The script logs each major action in the ETL process, including the start and end of each phase (extraction, transformation, and loading), as well as the start and end of the entire ETL job. This helps in tracking the progress and diagnosing issues in the ETL pipeline.

