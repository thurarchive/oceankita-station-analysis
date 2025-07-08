# OceanKita Station Analysis

OceanKita Station Analysis is a data-driven project designed to investigate how environmental factors—namely wind conditions, tidal movements, and rainfall intensity—influence the amount of debris observed in rivers across multiple monitoring stations. This analysis is guided by a set of targeted questions aimed at understanding whether and how these natural variables contribute to waste accumulation patterns. The project combines spatial and temporal data integration, statistical modeling, and exploratory analysis to support data-informed recommendations for environmental monitoring and river waste management.


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
- 📊 Exploratory Data Analysis: A structured Jupyter Notebook (OceanKita_Station_Analysis.ipynb) provides a step-by-step breakdown of data cleaning, transformation, and visual exploration.
- 🌬️ Environmental Factor Assessment: Investigates the influence of wind speed, tidal phase, and cumulative rainfall on river debris accumulation.
- 🌐 Multi-Station Insight: Compares behavior across multiple rivers to identify location-specific patterns and environmental sensitivities.
- 📈 Statistical Modeling: Includes correlation analysis and regression modeling to evaluate linear and interaction effects of environmental variables.
  

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
