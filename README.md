
## Project Structure

```
├── docker-compose.yaml      # Docker Compose setup for Airflow
├── main.py                  # Entry point or utility script
├── pyproject.toml           # Python project configuration
├── README.md                # This file
├── config/                  # Configuration files (if any)
├── dags/                    # All Airflow DAGs for the tutorial
│   ├── 1_first_dag.py
│   ├── 2_dag_versioning.py
│   ├── ...
│   └── dag_orchestrate_parent.py
├── logs/                    # Airflow logs
├── plugins/                 # Custom Airflow plugins
```
