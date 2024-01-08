#  Data Ingestion using Delta Live Tables


## Introduction
------------
Delta Live Tables is a declarative framework for building reliable, maintainable, and testable data processing pipelines. You define the transformations to perform on your data and Delta Live Tables manages task orchestration, cluster management, monitoring, data quality, and error handling.

Instead of defining your data pipelines using a series of separate Apache Spark tasks, you define streaming tables and materialized views that the system should create and keep up to date. Delta Live Tables manages how your data is transformed based on queries you define for each processing step. You can also enforce data quality with Delta Live Tables expectations, which allow you to define expected data quality and specify how to handle records that fail those expectations.

## Demo
------------
<p align="center">
  <img src=./documents/DLT_demo.gif>
</p>

## Architecture
------------
<p align="center">
  <img src=./documents/Medellian Arch.PNG>
</p>

