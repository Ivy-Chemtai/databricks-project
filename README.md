# Databricks-project

## Overview
This project implements a Medallion Architecture using Databricks and Delta Lake.

The pipeline follows:
Bronze → Silver → Gold

## Layers

### Bronze Layer
Raw data ingestion and initial storage using Delta format.

### Silver Layer
Data cleaning, transformation, and normalization.

### Gold Layer
Business-ready tables and dimensional models.

## Technologies Used
- Databricks
- Delta Lake
- PySpark
- Medallion Architecture
