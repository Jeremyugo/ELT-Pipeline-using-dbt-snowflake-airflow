# Data Pipeline Orchestration using DBT, Snowflake, Airflow

![image](https://github.com/user-attachments/assets/b4de1b4b-9c4b-493c-8fbc-6ae05e24aaee)

## Project Oragnization

This repo is organized into the following directories

```
.
└── dbt-dag          # containes all orchestration executables
    ├── dags
    │   └── dbt
    │       └── data_pipeline
    │           ├── analyses
    │           ├── dbt_packages
    │           ├── logs
    │           ├── macros
    │           ├── models
    │           ├── seeds
    │           ├── snapshots
    │           ├── target
    │           └── tests
    ├── include
    ├── plugins
    └── tests
        └── dags
```

- dbt-dag: contains all orchestration executables
- dbt-dag/dags/dbt/data_pipeline/

**Airflow DAG**
![alt text](image.png)
