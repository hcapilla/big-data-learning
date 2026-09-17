# Big Data Learning

A practical journey to learn Big Data and Data Engineering from the fundamentals to real-world projects.

This repository documents my learning process while exploring whether **Big Data and Data Engineering** are a professional path I would like to pursue.

The goal is not only to complete a course, but to understand the technologies, concepts and architectures behind modern data-intensive systems and apply them through practical exercises and personal projects.

---

## 🎯 Objectives

* Understand the fundamentals of Big Data and distributed computing.
* Learn how large-scale data is stored, processed and analyzed.
* Understand the problems that arise when data grows beyond the capabilities of traditional systems.
* Learn the Hadoop ecosystem.
* Learn Apache Spark and PySpark.
* Work with SQL and NoSQL databases.
* Build ETL/ELT data pipelines.
* Explore batch and stream processing.
* Learn the fundamentals of Data Engineering.
* Build practical Big Data projects.
* Document what I learn and the problems I encounter.
* Determine whether Big Data / Data Engineering is a field I would like to pursue professionally.

---

## 🧠 Background

I am a **Computer Engineer specialized in Computing**.

During my degree I had some exposure to areas related to Big Data, databases, programming and data processing. However, this repository is intended to approach Big Data as a structured learning path, starting from the fundamentals and progressively moving towards more advanced technologies and real-world architectures.

My previous experience includes:

* Python
* C / C++
* SQL
* MongoDB
* Machine Learning
* Computer Vision
* Artificial Intelligence
* Software Development
* Industrial Automation

This background will allow me to go deeper into the technical aspects as the learning path progresses.

---

## 🗺️ Learning Path

### 00 — Introduction

Understanding what Big Data actually is and why distributed systems are necessary.

Topics:

* What is Big Data?
* The 5 Vs
* Big Data vs traditional data processing
* Distributed computing
* Scalability
* Horizontal vs vertical scaling
* Batch vs streaming
* Data Engineering
* Data Science vs Data Engineering
* ETL vs ELT

---

### 01 — Big Data Fundamentals

Core concepts behind large-scale data systems.

Topics:

* Distributed systems
* Parallel processing
* Data partitioning
* Replication
* Fault tolerance
* Data locality
* Distributed storage
* Distributed processing

---

### 02 — Hadoop

Introduction to the Hadoop ecosystem.

Topics:

* Hadoop architecture
* HDFS
* NameNode
* DataNode
* MapReduce
* YARN
* Hive
* HBase

---

### 03 — Apache Spark

Learning the main distributed processing framework.

Topics:

* Spark architecture
* SparkSession
* RDDs
* DataFrames
* Transformations
* Actions
* Lazy evaluation
* Partitions
* Shuffles
* Caching
* PySpark

---

### 04 — Spark SQL

Working with structured data using Spark.

Topics:

* Spark SQL
* DataFrames
* SQL queries
* Joins
* Aggregations
* Window functions
* Data cleaning
* Performance considerations

---

### 05 — Data Engineering

Building complete data pipelines.

Topics:

* ETL
* ELT
* Data pipelines
* Data lakes
* Data warehouses
* Data quality
* Pipeline orchestration
* Apache Airflow
* Data formats
* Parquet
* JSON
* CSV

---

### 06 — Streaming

Processing data continuously as it arrives.

Topics:

* Event streaming
* Apache Kafka
* Producers
* Consumers
* Topics
* Partitions
* Offsets
* Spark Structured Streaming
* Real-time data processing

---

### 07 — NoSQL

Understanding databases designed for distributed and large-scale workloads.

Topics:

* NoSQL concepts
* Document databases
* Key-value databases
* MongoDB
* Cassandra
* Data modeling
* Replication
* Partitioning
* CAP theorem

---

### 08 — Data Warehousing

Understanding analytical data architectures.

Topics:

* Data warehouses
* OLTP vs OLAP
* Star schema
* Snowflake schema
* Dimensional modeling
* Data marts
* Analytical workloads

---

# 🚀 Projects

The learning process will include progressively more complex projects.

## Project 01 — Mini Project

A small project applying the concepts learned during the first stages of the course.

**Status:** 🔲 Not started

---

## Final Project — Industrial IoT Big Data Platform

A complete Big Data project inspired by industrial environments.

The project will simulate a large number of industrial sensors generating data continuously.

Example data:

```text
timestamp
machine_id
temperature
pressure
vibration
speed
energy_consumption
production_rate
error_code
```

Proposed architecture:

```text
Industrial Sensors
        │
        ▼
      Kafka
        │
        ▼
      Spark
        │
   ┌────┴─────┐
   ▼          ▼
Batch      Streaming
Processing  Processing
   │          │
   └────┬─────┘
        ▼
     Data Lake
        │
        ▼
 Data Warehouse
        │
        ▼
   Analytics
```

Potential features:

* Large-scale data generation
* Data ingestion
* ETL pipelines
* Batch processing
* Real-time processing
* Data storage
* Data quality checks
* Aggregations
* Anomaly detection
* Industrial KPIs
* Energy consumption analysis
* Machine monitoring
* Data visualization

**Status:** 🔲 Not started

---

# 📚 Learning Resources

The main learning resource for this repository is:

**IBM — Big Data, Hadoop, and Spark Basics**

Additional documentation, courses, books and resources will be added as the project progresses.

---

# 🛠️ Technologies

Technologies expected to be used throughout the learning path:

```text
Python
SQL
Apache Hadoop
HDFS
Apache Spark
PySpark
Spark SQL
Apache Kafka
Apache Airflow
MongoDB
Cassandra
PostgreSQL
Docker
Parquet
Git
```

Additional technologies may be added as the project evolves.

---

# 📈 Progress

| Topic                 | Status |
| --------------------- | ------ |
| Big Data fundamentals | 🔲     |
| Distributed computing | 🔲     |
| Hadoop                | 🔲     |
| HDFS                  | 🔲     |
| MapReduce             | 🔲     |
| Apache Spark          | 🔲     |
| PySpark               | 🔲     |
| Spark SQL             | 🔲     |
| ETL / ELT             | 🔲     |
| Data Engineering      | 🔲     |
| Apache Kafka          | 🔲     |
| Streaming             | 🔲     |
| NoSQL                 | 🔲     |
| Data Warehousing      | 🔲     |
| Final Project         | 🔲     |

---

# 💭 Why This Repository?

This repository is also an experiment.

I am exploring Big Data and Data Engineering to determine whether I would like to develop my career in this field.

Therefore, the repository will contain not only successful exercises, but also experiments, technical notes, mistakes and lessons learned along the way.

The objective is to understand the technology deeply enough to make an informed decision about my professional direction.

---

## 👨‍💻 Author

**Hernán Capilla Urbano**

Computer Engineer — Computing

[GitHub](https://github.com/hcapilla)
