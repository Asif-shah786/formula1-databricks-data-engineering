
Project Overview

We have formula1 dataset. For which we need to do data engineering. We need to load the dataset into data lakehouse, apply transformation, prepare it for analytics. During the process of creating ETL pipelines we need to make sure data governess, tracebility to data source.

Ingestion Requirement:

Loading all 6 dataset into data lakehouse
Apply correct schemas (columns, data types)
Add Audit Columns (ingestion )
initially full load, then incremental data load every sunday
Transformation Requirements:

Clean and Standardise data
Apply naming convention and reshape data - flattening nested data
Perform data quality checks - handling nulls, cleaning
Preservse bussiness keys
prepare data for gold layer
Reporting & Analytics Requirements:

Driver standing should be available for Each Season
Constructor standing should be available for each season as well
Analyze dominant driver and constructor
Support recent and historical analysis
Optimized for reporting and analytical queires
Support for geographical analysis
Non Functional Requirements

Every sunday
Complete if no new data available
Configure alerts
Solution should support to delete individual records
Solution should support time travel
