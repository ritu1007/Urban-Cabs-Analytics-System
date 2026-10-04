# Urban-Cabs-Analytics-System

An end-to-end data engineering and analytics solution built using Databricks, PySpark, and Lakeflow Declarative Pipelines to process and analyze urban cab booking data.

The system ingests raw cab trip and operational data from multiple sources, performs data cleansing and transformation using PySpark, and builds reliable analytical datasets through a multi-layer data pipeline. The solution uses Lakeflow Declarative Pipelines to implement scalable and maintainable data processing workflows.

Key Features - 

Ingested raw cab booking, trip, customer, driver, and operational data into the Databricks data platform.

Implemented Bronze, Silver, and Gold data layers for structured data processing.

Used PySpark for data cleansing, transformation, filtering, aggregation, and business-rule implementation.

Built Lakeflow Declarative Pipelines for automated and reliable data transformation workflows.

Performed data quality checks and handled duplicates, null values, and inconsistent records.

Created analytical datasets for metrics such as trip volume, revenue, customer activity, driver performance, and booking trends.

Implemented aggregations at different granularities such as daily, monthly, city, vehicle type, and customer segments.

Optimized transformation logic to efficiently process large volumes of cab transaction data.

Designed the pipeline to support downstream analytics and reporting requirements.

Technology Stack

Databricks | PySpark | Python | Lakeflow Declarative Pipelines | SQL | Delta Lake

Architecture

Raw Data → Bronze Layer → Silver Layer → Gold Layer → Analytics & Reporting

The project demonstrates practical implementation of modern data engineering concepts including ETL/ELT, Medallion Architecture, Delta Lake, PySpark transformations, data quality, pipeline orchestration, and scalable analytics processing.
