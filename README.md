# Olympic Data Analysis

# Project Overview
The goal of this project is to extract, load, transform, and analyze Olympic data to generate insightful reports and visualizations. By leveraging the power of Azure's data services, we ensure efficient data processing and seamless integration across various stages of the data pipeline.

# Architecture
![architecture](https://github.com/user-attachments/assets/15855eb9-1259-4a35-93e7-663948eb1d11)

# Steps Followed
  1. Establishing a Storage Account
  A Storage Account was created in Azure to facilitate robust data storage and management. This ensures that all data-related activities are performed securely and efficiently.
  ![Storage-container](https://github.com/user-attachments/assets/0442c298-88bc-4052-9858-6e06d9b75fed)
  
  2. Organizing Raw and Transformed Folders in the Container
  Within the Storage Account, containers were organized to separate raw data from transformed data. This enhances data organization and allows for better data management practices.

  3. Deploying Data Factory
  Azure Data Factory was deployed to optimize data orchestration and streamline workflows. Data Factory provides a platform to create and manage data pipelines that automate data movement and transformation.
  ![Data-Factory-Working](https://github.com/user-attachments/assets/b0b0a416-96ac-46fb-808a-d85dc3f5c3aa)

  7. Designing and Implementing a Data Pipeline
  Using Azure Data Factory Studio, designed a data pipeline and implemented. This pipeline ensures seamless data ingestion from the source to the Raw Data container in the Data Lake. The pipeline includes various activities to extract, load, and transform data as performed.
    1. Data Extraction: Connecting to the data source and retrieving raw data.
    2. Data Loading: Transferring the extracted data into the Raw Data container.
    3. Data Transformation: Applying necessary transformations to prepare the data for analysis.
  
  4. Validating and Debugging the Pipeline
  The pipeline was validated and debugged through processes to ensure data accuracy. This step is crucial to confirm that the data is correctly ingested and transformed without any errors.

  5. Storing Data Using Azure Data Lake Gen 2
  The data was stored in Azure Data Lake Gen 2 by sinking data from the pipeline into the respective containers. Azure Data Lake Gen 2 provides high-performance, secure, and scalable data storage solutions.

  6. Creating Compute on Azure Databricks
  An Azure Databricks Workspace was launched and configured. Compute resources were created, and a Cluster was formed for scalable data processing. Azure Databricks offers a unified analytics platform for big data and machine learning.

  7. Azure Synapse Analytics
     Designed a work space in synapse analytics to design a database table by connecting to datalake DB.

 8. Load Data into the Dedicated SQL Pool:
      Use the Data Factory pipeline or Databricks to load transformed data into the SQL pool.
      Ensure that the data is organized in a structured format suitable for reporting.
  9. Connect Power BI to Azure Synapse Analytics and create dashboards.

  ![Total_male_athletes](https://github.com/user-attachments/assets/aed26e0f-6291-4f7c-bc80-c5717058d2fe)

  
  ![Total Gold medals by Country ](https://github.com/user-attachments/assets/705cb528-e24f-4f4a-9f7b-26d024d8da93)


# Getting Started
1. Clone this repository.
2. Follow the steps outlined above to set up your Azure environment.
3. Run the Jupyter notebook to perform data extraction, loading, and transformation.

# Prerequisites
1. Azure Subscription
2. Basic knowledge of Azure services (Storage Account, Data Factory, Data Lake Gen 2, Databricks)
3. Familiarity with Python and Jupyter Notebooks

Resources: 
Azure Portal: https://azure.microsoft.com/en-ca/pricing/purchase-options/azure-account
Dataset link: https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo
