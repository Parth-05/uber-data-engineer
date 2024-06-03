# Uber Data Analysis Project

## Project Description

This project involves the analysis of Uber data from November 2023 to February 2024. The primary goal was to extract, transform, and load (ETL) the data using Apache Spark, create a data warehouse, and generate key performance indicators (KPIs) and insights. The final step was to visualize these insights using Tableau and publish a comprehensive dashboard.
![image](https://github.com/Parth-05/uber-data-analysis/assets/102514687/85a20609-eb38-4fa6-94df-0fef2c55f4cc)

Link to Tableau Dashboard - https://public.tableau.com/app/profile/parth.marathe/viz/Uber-data-analysis-viz/UBERDATAANALYSIS

Dataset Links:-
https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2024-01.parquet
https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2024-02.parquet
https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2023-12.parquet
https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2023-11.parquet
https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf
https://d37ci6vzurychx.cloudfront.net/misc/taxi_zone_lookup.csv

## Technologies and Languages Used

- **Apache Spark**: For ETL processes.
- **Tableau**: For data visualization.
- **Data Warehousing**: For efficient data storage and retrieval.
- **Python**: For scripting and data processing.
- **Jupyter Notebook**: For exploratory data analysis and prototyping.

- ## Project Architecture

1. **Data Extraction**: Extracted raw data from Uber's data sources.
2. **Data Transformation**: Processed and cleaned the data using Spark to ensure accuracy and consistency.
3. **Data Loading**: Loaded the transformed data into a data warehouse for efficient querying.
4. **Data Modeling**: Designed the data warehouse schema to support analysis.
5. **KPI Generation**: Identified and calculated key performance indicators.
6. **Data Visualization**: Created insightful visualizations using Tableau.
7. **Dashboard Publishing**: Published the Tableau dashboard to share insights.

- ## Data Model
- ![uber-datawarehouse-model](https://github.com/Parth-05/uber-data-analysis/assets/102514687/76a136aa-160e-44b5-84e6-0c48f1491ddf)

- ## How to Run the Project

1. **Setup Environment**: Ensure Apache Spark and Python are installed on your machine.
2. **Data Preparation**: Place the raw Uber data files in the specified directory.
3. **ETL Process**: Run the provided Spark scripts to perform ETL and load the data into the warehouse.
4. **Data Modeling**: Execute the data modeling scripts to create the data warehouse schema.
5. **Visualization**: Open the Tableau workbook and connect it to the data warehouse.
6. **Dashboard**: Publish the dashboard to Tableau Public or your Tableau Server.

7. ## Conclusion

This project demonstrates the end-to-end process of data analysis, from ETL and data modeling to KPI generation and visualization. By leveraging Spark and Tableau, the project provides actionable insights into Uber's operational data, highlighting trends and performance metrics. The final dashboard serves as a powerful tool for decision-making and strategic planning.
