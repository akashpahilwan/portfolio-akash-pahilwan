---
date: '1'
title: 'End to End ETL Architecture and orchestration'
cover: './ETL.png'
github: 'https://github.com/akashpahilwan/astro-airflow/tree/main/docs/process_employee'
tech:
  - ADF
  - Snowflake
  - Python/Jinja
  - DBT
  - Airflow
---

Created an ETL project using variety of tools. Used [Azure Data Factory](https://azure.microsoft.com/en-in/products/data-factory) for extraction, [Snowflake](https://www.snowflake.com/en/) for data warehousing, [DBT](https://www.getdbt.com/) for transformation adn laoding into target tables which exist in snowflake and used [Airflow](https://airflow.apache.org/) for orchestration. Also used [Postgres](https://www.postgresql.org/) for logging the failure details and [slack](https://slack.com/intl/en-in)/Email to notify users of pipeline failures.
