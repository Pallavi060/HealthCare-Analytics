# Healthcare Analytics - Data Engineering Assignment

## Overview

This repository contains the solution for the Healthcare Analytics assignment, focusing on data engineering tasks such as data processing, transformation, and integration. The dataset used is the "Health Insurance Marketplace Analysis" from Kaggle, which includes information about individual medical costs billed by health insurance.

## Tasks

### 1. Ingestion and ETL

- **Data Ingestion:** The dataset is loaded using Google Colab for initial exploration and transformation. Databricks is then employed for scalable ETL processes.
  
- **ETL Job:** The ETL job is implemented using PySpark in Databricks. The code is organized into a notebook named `Healthcare_Analytics_ETL.ipynb`.
  
- **Data Transformation:** Various transformations are applied to clean and structure the data, including handling null values, standardizing formats, and creating derived features.
  
- **Data Storage:** The transformed data is stored in a parquet format on a Databricks File System (DBFS).
  
- **Bonus:** Unit tests for the ETL job are included in the notebook to ensure the correctness of the transformations.

### 2. Data Quality Checks

- Data quality checks are implemented to ensure the integrity of the transformed data. This includes checking for null values and verifying the correctness of transformation logic.

### 3. Data Analysis

- SQL queries are utilized to analyze the data, focusing on understanding market dynamics for health insurance plans.

### 4. Output

- The notebook `Healthcare_Analytics_Output.ipynb` presents the analysis results, providing insights into health insurance plan distribution and characteristics across different states and age groups.
  
- A targeted marketing strategy is developed based on the analysis, recommending the top 5 avenues where marketing effort should be spent by plan, age, and state.

## Technologies Used

- **Google Colab:** Used for initial data exploration and development of the ETL code.
  
- **Databricks:** Employed for scalable ETL processes and data storage. The code can be imported into Databricks and executed seamlessly.
  
- **PySpark:** Utilized for data manipulation and transformation in the ETL process.
  
- **SQL:** Employed for data analysis queries.

## Challenges Faced

- **Google Colab Limitations:** Google Colab may have limitations in terms of scalability and processing large datasets. Therefore, initial data exploration is performed in Colab, and the heavy lifting ETL processes are transitioned to Databricks.
  
- **Databricks Setup:** Setting up Databricks clusters and ensuring proper connectivity can be challenging. Clear instructions for cluster setup and notebook execution are provided in the README.

## How to Run the Code

1. Open and run the `Healthcare_Analytics_ETL.ipynb` notebook in Google Colab for initial exploration.
  
2. Import the notebook into Databricks for scalable ETL processes.
  
3. Execute the `Healthcare_Analytics_Output.ipynb` notebook for data analysis and marketing strategy recommendations.

## Additional Setup

- For Databricks setup, follow the instructions in the `Databricks_Setup_Guide.md` file.

## Conclusion

This solution demonstrates a comprehensive approach to healthcare analytics, encompassing data engineering tasks and providing actionable insights for targeted marketing strategies. The combination of Google Colab and Databricks offers a scalable and efficient solution for processing and analyzing large healthcare datasets.

### Tags

#DataEngineering #HealthcareAnalytics #ETL #GoogleColab #Databricks #PySpark #SQL #DataAnalysis
