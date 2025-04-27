# NYC-payroll-project

## Project Introduction

The City of New York would like to develop a Data Analytics platform on Azure Synapse Analytics to accomplish two primary objectives:
<li>Analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.
<li>Make the data available to the interested public to show how the City’s budget is being spent on salary and overtime pay for all municipal employees.

The main goals are to create high-quality data pipelines that are dynamic, can be automated, and monitored for efficient operation. The project team also includes the city’s quality assurance experts who will test the pipelines to find any errors and improve overall data quality.

The source data resides in Azure Data Lake and needs to be processed in a NYC data warehouse in Azure Synapse Analytics. The source datasets consist of CSV files with Employee master data and monthly payroll data entered by various City agencies.

## Project Environment
For this project, I worked in the Azure Portal, using several Azure resources, including:
<li>Azure Data Lake Gen2
<li>Azure SQL DB
<li>Azure Data Factory
<li>Azure Synapse Analytics

## Project steps
The project was divided into 6 steps to organize and allow for the correct management.

### Step 1: Prepare the Data Infrastructure
The data infrastructure involves the creation of the following resources:
- <b>Azure Data Lake Storage Gen2</b> (storage account) and associated storage container resource to upload the raw data.
- <b>Azure Data Factory Resource</b>.
- <b>SQL Database</b> and the table to store the current year's data.
- <b>Synapse Analytics workspace</b> and the master data tables.

### Step 2: Create Linked Services
In the Azure Data Factory, three Linked Services were created:
- To Azure Data Lake
- To SQL Database
- To Synapse Analytics

### Step 3: Create Datasets in Azure Data Factory
In the Azure Data Factory, the Datasets were created to load the raw data and to save the transformed data.

### Step 4: Create Data Flows


### Step 5: Data Aggregation and Parameterization
### Step 6: Github connection


