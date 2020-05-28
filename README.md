Data Engineering Guide
==========================

This is a repo with tools used in data engineering

# Databases
* Column
    * [AWS Redshift](https://aws.amazon.com/redshift/) A fully-managed petabyte-scale cloud based data warehouse product designed for large scale data set storage and analysis.
    * [Cassandra](https://cassandra.apache.org/) A SGBD designed to handle large amounts of data across many commodity servers, providing high availability with no single point of failure.
* Document
    [MongoDB](https://www.mongodb.com) A cross-platform document-oriented database, uses JSON-like documents with optional schemas.
* Relational
    * [MySQL](https://www.mysql.com/) The most popular Open Source SQL database management system.
    * [Oracle](https://www.oracle.com/database/) A robust, reliable and safe SGBD.
    * [PostgreSQL](https://www.postgresql.org/) A powerful open source object-relational database system.
    * [SQLServer](https://docs.microsoft.com/en-us/sql/sql-server/) A database management system developed by Microsoft.

# File Format (serialization)
* [Apache Avro](https://avro.apache.org) A row-oriented serialization that use JSON for defining data types and protocols.
* [Apache Parquet](https://parquet.apache.org) An open-source column-oriented serialization, it's specialized in efficiently storing and processing nested data types.
* [Apache ORC](https://orc.apache.org/) A column-oriented serialization highly optimized for reading and writing.

# Pipeline Orchestration
* [Apache Airflow](https://github.com/apache/airflow) An open-source workflow management plataform, it schedule workflows and monitor them via your own UI.
* [Azkaban](https://azkaban.github.io/) A batch workflow job scheduler.
* [Kedro](https://github.com/quantumblacklabs/kedro) A development workflow framework that implements software engineering best-practice for data pipelines.
* [Luigi](https://github.com/spotify/luigi) Helps you to build batch jobs pipelines and monitor them all.
