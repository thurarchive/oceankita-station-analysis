# OceanKita Station Analysis

OceanKita Station Analysis is a data-driven project focused on exploring, analyzing, and visualizing oceanographic data collected from multiple monitoring stations. The goal is to gain insights into key environmental parameters—such as temperature, salinity, and other sensor readings—to better understand the marine environment and support research, conservation, and policy-making efforts.

## Overview

The analysis focuses on:
1. Cleaning and preprocessing of raw station data.
2. Exploratory data analysis (EDA) to uncover spatial and temporal patterns.
3. Visualization of variables across stations and time.
4. Statistical summaries and insights for further interpretation.

All analysis is conducted using Python in a Jupyter Notebook (`OceanKita_Station_Analysis.ipynb`).

## Data Sources
- Parameter Lingkungan.csv: Contains environmental parameters (e.g., temperature, salinity) measured at various stations.
- dataset/Data.csv & dataset/dl.csv: clean datasets from OceanKita’s monitoring stations.

## Key Features
- 📊 Interactive Data Analysis: Jupyter Notebook (OceanKita_Station_Analysis.ipynb) for step-by-step data exploration and visualization.
- 🌊 Environmental Monitoring: Focus on critical oceanographic variables relevant to marine science and resource management.
- 🗺️ Multi-Station Comparison: Analyze and compare data across different monitoring locations.
  

## Repository Structure

```
oceankita-station-analysis/
├── dataset/                          # Dataset directory
├── OceanKita_Station_Analysis.ipynb  # Main analysis notebook
└── README.md                         # Project documentation
└── requirements.txt                  # Project dependencies 
```

## Usage

1. Clone the repository:
```
git clone https://github.com/yourusername/OceanKita-Station-Analysis.git
```
### Requirements
- Python 3.8+
- pandas
- matplotlib
- seaborn
- numpy
- geopandas (if spatial visualization included)

Install all dependencies via:
```bash
pip install -r requirements.txt
```
2. Open the Jupyter Notebook:
Launch OceanKita_Station_Analysis.ipynb to explore the analysis and visualizations.
3. Explore the Data:
Review the datasets in the dataset/ folder and Parameter Lingkungan.csv for more details.


## Acknowledgements

This analysis is developed for **OceanKita** as part of their ocean monitoring and research efforts.
