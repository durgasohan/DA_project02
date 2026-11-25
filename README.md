# Superstore Sales Analysis

This project analyzes the Sample Superstore dataset with pandas and includes Power BI dashboard files.

## Project files

- `Sample - Superstore.csv` - source dataset used by the notebook.
- `superstore_pandas_analysis.ipynb` - data cleaning, exploratory analysis, KPIs, and visualizations.
- `Executive_Dashboards.pbix` and `Executive_Overview.pbix` - Power BI dashboards.
- `Report/` - Power BI report definition and resources.

## Run the notebook

From the project directory, create an environment and install the dependencies:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m jupyter lab
```

Open `superstore_pandas_analysis.ipynb` and run the cells from top to bottom. The notebook reads the CSV from the project directory and writes generated CSV reports under `analysis_outputs/`.

Open either `.pbix` file in Power BI Desktop to view the dashboards.
