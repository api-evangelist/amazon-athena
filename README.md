# Amazon Athena

Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.

## Overview

The Amazon Athena API enables programmatic control over query executions, named queries, work groups, data catalogs, databases, table metadata, and prepared statements. It enables building serverless analytics solutions backed by data stored in Amazon S3.

## API Documentation

- **Human URL:** https://docs.aws.amazon.com/athena/latest/APIReference/Welcome.html
- **Base URL:** https://athena.us-east-1.amazonaws.com

## Features

- Serverless SQL query execution against Amazon S3 data
- Pay-per-query pricing with no infrastructure management
- Support for standard ANSI SQL with complex joins and window functions
- Integration with AWS Glue Data Catalog for schema management
- Named queries for saving and reusing SQL statements
- Work groups for query isolation and cost management
- Prepared statements for parameterized query execution
- Multiple data format support including Parquet, ORC, JSON, CSV
- Query result caching for improved performance and cost reduction
- Fine-grained access control with IAM and Lake Formation

## Use Cases

- Analyze log files and clickstream data stored in S3
- Run ad-hoc SQL queries on data lake without ETL
- Build serverless data pipelines and reporting solutions
- Query AWS service logs including CloudTrail, ELB, and VPC Flow Logs
- Perform cost analysis on AWS Cost and Usage Reports
- Enable self-service analytics for business intelligence teams

## Artifacts

### OpenAPI Specification
`openapi/amazon-athena-openapi.yml`

Complete OpenAPI 3.1.0 specification covering all Athena API paths.

### Spectral Rules
`rules/amazon-athena-spectral-rules.yml`

### Naftiko Capabilities
- `capabilities/shared/athena-api.yaml` — Shared per-API capability definition
- `capabilities/sql-analytics.yaml` — Workflow capability for SQL analytics

### Vocabulary
`vocabulary/amazon-athena-vocabulary.yaml`

### JSON Schemas
`json-schema/` — 98 JSON Schema files for all objects.

### JSON Structures
`json-structure/` — 98 JSON Structure files.

### JSON-LD Context
`json-ld/amazon-athena-context.jsonld`

### Examples
`examples/` — 98 example JSON files.

## Integrations

- Amazon S3
- AWS Glue
- Amazon QuickSight
- AWS Lake Formation
- Amazon CloudWatch
- AWS IAM
- Amazon DynamoDB
- AWS Step Functions
- Amazon SageMaker
- Apache Spark

## Tags

Amazon Athena, SQL, Analytics, Serverless, AWS

## Maintainers

- Kin Lane (kin@apievangelist.com)
