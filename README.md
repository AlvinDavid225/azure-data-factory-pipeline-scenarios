Azure Data Factory Pipeline Scenarios

A collection of real-world Azure Data Factory pipelines demonstrating production-grade data engineering patterns such as dynamic ingestion, metadata monitoring, conditional processing, pipeline observability, and API orchestration.

This repository showcases ADF architecture thinking and pipeline design, not just basic tutorials.

Architecture Overview

Data Flow
Source Systems
      ↓
Azure Data Factory (Orchestration)
      ↓
Azure Data Lake Storage Gen2
      ↓
Azure SQL Database
      ↓
Analytics / Reporting
Scenario Projects

This portfolio contains 6 scenario-based Azure Data Factory projects.

Project	Description
Dynamic File Processing Pipeline	Automate ingestion of files using wildcard filters and dynamic parameters
Data Lake Metadata Monitoring	Monitor folder structure and capture metadata into SQL
Conditional File Processing	Process files based on business conditions using control tables
Pipeline Monitoring & Logging	Implement pipeline observability, logging, and alerting
API Integration Pipeline	Trigger pipelines via REST APIs and secure endpoints
Control Flow Automation	Implement advanced pipeline logic and expressions
Technologies Used
Azure Data Factory
Azure Data Lake Storage Gen2
Azure SQL Database
REST API
Azure Log Analytics
ADF Control Flow Activities
Azure Data Factory Fundamentals Covered

This project demonstrates several core ADF concepts.

Copy Data Activity

Wildcard Filters

Schema Mapping

Fault Tolerance

Session Logging

Parameters vs Variables

Compression and Decompression

Partition Discovery

Metadata Activity

Delete Files After Copy

Copy Behaviour

Monitoring Pipelines

List Files in Storage

Last Modified Filter

Additional Columns in Copy Activity

Repository Structure
azure-data-factory-pipeline-scenarios
│
├── architecture
│   └── architecture-overview.png
│
├── fundamentals
│   └── adf-fundamentals.md
│
├── projects
│
│   ├── 01-dynamic-file-processing
│   ├── 02-data-lake-metadata-monitoring
│   ├── 03-conditional-file-processing
│   ├── 04-pipeline-monitoring-logging
│   ├── 05-api-integration
│   └── 06-control-flow-automation
Example Pipeline Design
ADLS Landing Zone
        ↓
ADF Pipeline
        ↓
Copy Activity
        ↓
Processed Storage
        ↓
Azure SQL Database
Purpose of This Repository

The goal of this project is to demonstrate production-style Azure Data Factory pipelines used in real-world data engineering workflows.

This repository highlights:

pipeline orchestration

metadata-driven pipelines

conditional workflows

monitoring and logging

API integration

control flow automation

Author

Alvin David

Aspiring Azure Data Engineer focused on building production-ready data pipelines using Azure Data Factory and modern data engineering tools.
