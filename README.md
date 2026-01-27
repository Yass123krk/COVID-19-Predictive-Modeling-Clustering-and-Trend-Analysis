# COVID-19 Global Data Analysis using PySpark

## Machine Learning & Big Data Project

---

## Project Overview

This project presents a complete analysis of a global COVID-19 dataset using
**Apache Spark (PySpark)** in a **Big Data analytics context**.

The project is academically validated and fully completed. The objective is to
demonstrate how distributed data processing and analytical techniques can be
applied to large-scale, time-series health data.

The work focuses on:
- Large-scale data ingestion and cleansing
- Temporal and geographical analysis
- Statistical aggregation at multiple levels
- Trend analysis and clustering
- Performance evaluation of distributed computations

All methodology, results, and interpretations are documented in the accompanying report.

---

## Implemented Analyses

The project is organized around three main analytical tasks:

- **Country-level analysis**
  - Monthly average of daily confirmed COVID-19 cases
  - Comparative temporal analysis across countries

- **Continent-level analysis**
  - Weekly statistics (mean, standard deviation, minimum, maximum)
  - Cross-continent comparison

- **Trend and clustering analysis**
  - Trendline coefficient computation
  - K-Means clustering (K = 4) on the most affected regions
  - Geographical and statistical visualizations

---

## Repository Structure

```bash
project-root/
├── notebooks/
│ └── MLBD_Pyspark.ipynb # Main analysis notebook
│
├── data/
│ ├── raw/ # Raw input datasets
│ ├── processed/ # Cleaned datasets
│ └── results/ # Final analytical outputs
│
├── docs/
│ ├── report.pdf # Academic report
│ └── figures/ # Figures used in the report
│
├── README.md
└── .gitignore
```bash

---

## Data Workflow

1. Raw datasets are stored in `data/raw`
2. Cleaning and preprocessing outputs are stored in `data/processed`
3. Analytical results are exported to `data/results`
4. Figures are generated for reporting and interpretation

This structure ensures clarity, reproducibility, and traceability.

---

## How to Run the Project

### Prerequisites

- Python 3.x
- Apache Spark
- PySpark
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - geopandas
  - plotly

---

### Execution

All analyses are executed through the main Jupyter Notebook:

```bash
notebooks/MLBD_Pyspark.ipynb
```

Running the notebook from top to bottom reproduces all results and figures.

---

## Results and Performance

- Analytical outputs are exported as CSV files
- Execution time is measured for each major task
- Performance analysis highlights the trade-offs between
  distributed processing overhead and scalability

Detailed interpretations are available in the report.

---

## Report

A complete academic and technical description of:
- Methodology
- Mathematical foundations
- Implementation details
- Results and interpretations
- Ethical considerations

is available in:

```bash
docs/report.pdf
```

---

## Author

Yasser El Karkouri  
Data Engineering / Machine Learning / Big Data