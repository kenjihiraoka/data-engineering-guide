Data Engineering Guide
==========================

This is a repo with tools used in data engineering

# Databases
* Column
    * [AWS Redshift](https://aws.amazon.com/redshift/) A fully-managed petabyte-scale cloud based data warehouse product designed for large scale data set storage and analysis.
    * [Cassandra](https://cassandra.apache.org/) A SGBD designed to handle large amounts of data across many commodity servers, providing high availability with no single point of failure.
* Distributed
    * [Datomic](https://www.datomic.com) High-throughput system, such as a time-series database or log store.
* Document
    * [MongoDB](https://www.mongodb.com) A cross-platform document-oriented database, uses JSON-like documents with optional schemas.
* Relational
    * [MySQL](https://www.mysql.com/) The most popular Open Source SQL database management system.
    * [Oracle](https://www.oracle.com/database/) A robust, reliable and safe SGBD.
    * [PostgreSQL](https://www.postgresql.org/) A powerful open source object-relational database system.
    * [SQLServer](https://docs.microsoft.com/en-us/sql/sql-server/) A database management system developed by Microsoft.

# File Format (serialization)
* [Apache Avro](https://avro.apache.org) A row-oriented serialization that use JSON for defining data types and protocols.
* [Apache Parquet](https://parquet.apache.org) An open-source column-oriented serialization, it's specialized in efficiently storing and processing nested data types.
* [Apache ORC](https://orc.apache.org/) A column-oriented serialization highly optimized for reading and writing.
* [Delta Lake](https://delta.io/) An open-source storage layer that brings reliability to data lakes.

# Pipeline Orchestration
* [Apache Airflow](https://github.com/apache/airflow) An open-source workflow management plataform, it schedule workflows and monitor them via your own UI.
* [Azkaban](https://azkaban.github.io/) A batch workflow job scheduler.
* [Kedro](https://github.com/quantumblacklabs/kedro) A development workflow framework that implements software engineering best-practice for data pipelines.
* [Luigi](https://github.com/spotify/luigi) Helps you to build batch jobs pipelines and monitor them all.

# Stream Pipelines
* [Apache Hudi](https://hudi.apache.org/) An open source framework for managing storage for real time processing, one of the most interesting feature is the Upsert.
* [Apache NiFi](https://nifi.apache.org/) Automate your data flow between systems with reliable and no single point of failure.
* [Apache Flink](https://flink.apache.org/) An open-source stream-processing framework, provides multiple APIs at different levels of abstraction and offers dedicated libraries for common use cases.
* [Spark Streaming](https://spark.apache.org/streaming/) An extension of the core Spark that enables scalable, high-throughput, fault-tolerant stream processing of live data streams.
