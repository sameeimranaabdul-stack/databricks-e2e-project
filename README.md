# End-to-End Databricks Data Engineering Project

## Overview
An end-to-end Lakehouse data engineering solution built on Azure Databricks, featuring Unity Catalog governance, Delta Lake storage, Spark Declarative Pipelines, and automated Lakeflow Jobs.

## Repository Structure
- **`delta_lake/`** – Delta Lake table management, ACID transactions, schema evolution, and time-travel operations.
- **`spark_declarative_pipelines/`** – Medallion architecture (Bronze, Silver, Gold) declarative ETL pipelines built with PySpark and Spark SQL.
- **`lakeflow_jobs/`** – Automated multi-task workflow orchestration, scheduling, and pipeline dependencies.
- **`unity_catalog/`** – Centralized data governance, catalog/schema organization, data lineage, and fine-grained access controls.
- **`projects/databricks-e2e-project/`** – End-to-end integration notebooks combining ingestion, transformation, and curated analytics outputs.

## Tech Stack
- **Platform:** Azure Databricks, Unity Catalog, Lakeflow Jobs
- **Storage & Processing:** Delta Lake, PySpark, Spark SQL, Spark Declarative Pipelines
