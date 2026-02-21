# PySpark Notebook

Small workspace for running the included PySpark Jupyter notebook.

## Contents

- `PySpark.ipynb`: main notebook
- `requirements.txt`: Python dependencies

## Prerequisites

- Python 3.10+ (3.11 is fine)
- Java 8/11/17 (required by Spark)

## Setup

```bash
python -m venv .venv
# Windows PowerShell
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Run

```bash
jupyter notebook
```

Open `PySpark.ipynb` and run the cells.

## Notes

If Spark fails to start, verify `JAVA_HOME` is set and that Java is on your PATH.
