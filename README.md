# Olympic Data Analysis
This project involves analyzing Olympic data using various tools and technologies, including Azure Data Factory, Data Lake Gen 2, Synapse Analytics, and Azure Databricks.

# Project Overview
The project aims to extract, load, and transform Olympic data to generate insightful reports and visualizations. The steps followed in this project include setting up Azure services, creating a data pipeline, and processing the data for analysis.

# Steps Followed
  1. Establishing a Storage Account
  A Storage Account was created in Azure to facilitate robust data storage and management. This ensures that all data-related activities are performed securely and efficiently.
  2. Organizing Raw and Transformed Folders in the Container
  Within the Storage Account, containers were organized to separate raw data from transformed data. This enhances data organization and allows for better data management practices.
  3. Deploying Data Factory
  Azure Data Factory was deployed to optimize data orchestration and streamline workflows. Data Factory provides a platform to create and manage data pipelines that automate data movement and transformation.
  4. Designing and Implementing a Data Pipeline
  Using Azure Data Factory Studio, a data pipeline was designed and implemented. This pipeline ensures seamless data ingestion from the source to the Raw Data container in the Data Lake. The pipeline includes various activities to extract, load, and transform data as required.
  5. Validating and Debugging the Pipeline
  The pipeline was validated and debugged through meticulous processes to ensure data accuracy. This step is crucial to confirm that the data is correctly ingested and transformed without any errors.
  6. Storing Data Using Azure Data Lake Gen 2
  The data was stored in Azure Data Lake Gen 2 by sinking data from the pipeline into the respective containers. Azure Data Lake Gen 2 provides high-performance, secure, and scalable data storage solutions.
  7. Creating Compute on Azure Databricks
  An Azure Databricks Workspace was launched and configured. Compute resources were created, and a Cluster was formed for scalable data processing. Azure Databricks offers a unified analytics platform for big data and machine learning.

# Next Steps(Part 2):
  1. Connect Azure Synapse Analytics with Power BI to create insightful reports for enhanced data visualization and analysis.
  2. Further analyze and process the data using Azure Databricks.
  3. Files - olympic-data-analysis.ipynb: The Jupyter notebook containing the code for extracting, loading, and transforming Olympic data using Azure Databricks.

# Getting Started
1. Clone this repository.
2. Follow the steps outlined above to set up your Azure environment.
3. Run the Jupyter notebook to perform data extraction, loading, and transformation.

# Prerequisites
1. Azure Subscription
2. Basic knowledge of Azure services (Storage Account, Data Factory, Data Lake Gen 2, Databricks)
3. Familiarity with Python and Jupyter Notebooks
