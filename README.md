# global_unicorn_datafactory_pipeline

<br>

## An automated data pipeline using Microsoft Azure Data Factory, a cloud service that enables ETL data process.

<br>

## Design of the Pipeline:


### 1) Raw data from an excel file gets loaded into Azure data lake gen 2, an Azure cloud storage service.


### 2) Data lake gets mounted into Azure Databricks which is used to perform data cleaning and transformation on the dataset.


### 3) After data transformation, the cleaned data is loaded back into Azure data lake gen2.


### 4) On failure or successful execution of the pipeline, the engineer receives an email alert


### 5) Power BI connects to data lake gen2 to enable data visualization.


### All these processes are being automated using Azure Data Factory. The moment new data is uploaded into the data lake, the pipeline begins its operation

<br>

![pipeline image](./pipeline.png)


## Power BI Dashboard soon be updated