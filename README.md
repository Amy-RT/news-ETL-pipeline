# AI News ETL Pipeline
An Automated ETL pipeline to retrieve AI related news articles from the Google News API and load them into an SQLite database. The pipeline is automated using Apache Airflow.
This project was completed on the Educative virtual environment as a guided project. <br/>

Data is extracted from the JSON API results, cleaned and then transformed into a pandas dataframe. The dataframe is loaded into an SQLite database. XComs are utilised to pass data between tasks within the DAG run. <br/>

A screenshot of successful pipeline execution:
<img width="760" height="381" alt="image" src="https://github.com/user-attachments/assets/b8cb5e7c-ead0-4362-ab36-717f3307f8bf" />

