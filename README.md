# BigQuery
BigQuery is a fully managed enterprise data warehouse that helps you manage and analyze your data with built-in features like machine learning, geospatial analysis, and business intelligence. <br>

| Functions | Details |
|:---|:---|
|**Ingest**| - Batch (No costs) & Streaming <br> - Structured & Semi-structured data |
|**Store**| - Up to Petabytes of data <br> - Datasets (regouped data as folders) & tables (usual data in tabular format) <br> - Federate data (from Cloud Storage) |
|**Analyze**| - Super-fast SQL queries <br> - Aggregate <br> - Transform with DML (Data Manuplate Language) |
|**Visualize**| - Export and connect to other tools more easily |
<br>

# 1. BigQuery storage
BigQuery stores data using a columnar storage format that is optimized for analytical queries. BigQuery presents data in tables, rows, and columns and provides full support for database transaction semantics (ACID). BigQuery storage is automatically replicated across multiple locations to provide high availability.<br>

**Load data into BigQuery using**:
- Stream data with the Storage Write API.
- Batch-load data from local files or Cloud Storage using formats that include: Avro, Parquet, ORC, CSV, JSON, Datastore, and Firestore formats.

You can export the result with complicated queries to a table as Destination such as following tables.
- **Native table** (similar to Dedicated SQL pool in Azure Synapse Analytics) <br>
- **External table** (similar to External Table on Serverless SQL Pool in Azure Synapse Analytics - for Ad hoc and One time analysis) <br>
Federated queries let you read data from external sources while streaming supports continuous data updates so that you can avoid duplicate storage.


# Optimize BigQuery
- Leverage caching and materialized veiws <br>
- Partition and cluster your BigQuery tables <br>
- Data retention policies <br>
- Avoid duplicate storage - use federated data access <br>

- 
