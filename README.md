## ⚠️ Important Notice

The API key or demo credentials included in this repository are **for demonstration purposes only**. 

- **These keys have been deactivated and are no longer valid.**
- Please use your own API keys or credentials when testing or deploying this project.

## Architecture Diagram Flow
- Data is sourced from Kaggle, uploaded as CSV files.
- The data is then pushed into Cloud Storage.
- Airflow orchestrates the ETL process, validating the data with Cosmos.
- The data is then transformed using dbt and stored in BigQuery.
- Metabase creates interactive dashboards and reports based on the data stored in BigQuery.
  
![arch_diagram](https://github.com/user-attachments/assets/78487850-b2ee-45a3-b2dc-5072aab0f3ed)

## Data Flow
![data_flow](https://github.com/user-attachments/assets/156cce7b-b73f-446d-93e5-7e87bebbe9fa)

## Dashboard
![dashboard](https://github.com/user-attachments/assets/f49d920a-d4b7-4eb9-9cce-c9e46c4e27c0)
