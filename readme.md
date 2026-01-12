# Spark Data Quality Checks (PySpark)

## Project Summary


---

## Architecture

- Apache Spark (PySpark)
- JupyterLab
- Docker
- pytest for Spark-based unit tests

---

## What This Demonstrates

---

## How to Run

### Prerequisites
- Docker
- Docker Compose

### Steps

```bash
git clone https://github.com/dominik-mikulski/EDA-Spark-Notebook.git
cd EDA-Spark-Notebook/docker
docker compose up
```

Open JupyterLab:

```
http://localhost:8900
```

Open the notebook:

```
notebooks/spark_eda.ipynb
```

---

## Example Usage

---

## Spark UI (Performance & Jobs)

When a Spark job is running, the Spark Web UI is available at:

```
http://localhost:4050
```

Additional Spark applications may use ports:

```
4051–4059
```

The Spark UI allows inspection of:
- Jobs and stages
- Task execution details
- DAG visualization
- Shuffle and storage metrics

This is useful for debugging and performance analysis.

---

## Project Structure

```text
DQ-Spark-Notebook/
├── data/        # Sample datasets
├── docker/      # Docker Compose configuration
├── notebooks/   # Demo notebook
└── README.md
```

## Design Decisions

## Notes
