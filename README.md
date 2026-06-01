# Databricks Notebooks

**Databricks SQL · Delta Lake · PySpark · Azure**

A collection of Databricks notebooks demonstrating modern data 
engineering patterns including SQL analytics, Delta Lake time 
travel, and PySpark transformations on healthcare project data.

## Notebooks

| Notebook | Concepts covered |
|----------|-----------------|
| [01_sql_window_functions](notebooks/01_sql_window_functions.ipynb) | CTEs, RANK, LAG/LEAD, variance analysis in Databricks SQL |
| [02_delta_lake_intro](notebooks/02_delta_lake_intro.ipynb) | Delta tables, time travel, MERGE INTO upsert logic |
| [03_pyspark_basics](notebooks/03_pyspark_basics.ipynb) | DataFrames, filter, groupBy, writing to Delta |

## Key concepts demonstrated

| Concept | Description |
|---------|-------------|
| Delta Lake | ACID transactions, versioned data storage |
| Time travel | Query historical data with VERSION AS OF |
| MERGE INTO | Production-grade upsert logic |
| PySpark | DataFrame API for distributed data processing |
| End-to-end pipeline | Raw table → transform → write to Delta |

## Screenshots
Query results and output previews are in the `/screenshots` folder.

## Dataset
Built on a synthetic healthcare project tracking dataset modeled
after real operational data in behavioral health environments.
Same dataset used across all portfolio repos for consistency.

---
Built by Alejandra Kheng · [LinkedIn](https://linkedin.com/in/alejandra-g-952a58143/)
