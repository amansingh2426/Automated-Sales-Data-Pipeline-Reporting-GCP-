# Google Cloud Data Analytics Project

This repository contains code and configuration files for Google Cloud Data Analytics Project.This project demonstrates the integration of several GCP services to create an efficient and automated data pipeline for sales data. We'll show you how to:


<img width="1027" height="555" alt="Screenshot 2025-12-26 192726" src="https://github.com/user-attachments/assets/40793934-695d-41a6-a518-d145067ca411" />






## Overview

1. **Web Portal**: Built with Python Flask to allow users to upload sales data files.
2. **Storage**: Uploaded files are stored in a GCS bucket.
3. **Cloud Function**: Automatically triggered when a file is uploaded to the GCS bucket, extracts data from the file, and loads it into BigQuery.
4. **ETL Process**: Extract, Transform, Load process implemented to handle data from raw upload to processed state.
5. **Reporting**: Summary views and dashboards in Looker Studio for key metrics, with filtering and drill-down capabilities.



<img width="1026" height="551" alt="Screenshot 2025-12-26 192823" src="https://github.com/user-attachments/assets/729dd601-0947-4142-a516-1dc13f0d1f53" />


## Architecture
<img width="1072" height="437" alt="Screenshot 2025-12-26 192916" src="https://github.com/user-attachments/assets/ed38544d-d409-472d-9960-3890879b0051" />

