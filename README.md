# Data_Engineering_2020_tokyo_olympics
Steps:
 - Creation of storage account in Microsoft Azure.
 - Creation of pipelines from this github repository (data file in this repository) to Azure database (e.g. Datalake).
 - Creation of App registration ID and Secret Key to use it to connect to the Azure database using Python (auth using library Spark).
 - Use of Databricks along with Python (library Spark) to extract raw data from Azure database, transform them into a proper format, and load them back to database (code for this step in ipynb file in this repository).

Use of Synapse Analytics in Microsoft Azure contains all the above steps and allows for Data Analysis. 

