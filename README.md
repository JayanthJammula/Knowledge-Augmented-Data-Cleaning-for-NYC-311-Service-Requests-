# Knowledge Augmented Data Cleaning for NYC 311 Service Requests

## Overview

This project processes and analyzes data, computes metrics, and generates a scatterplot over New York City boundaries. It consists of three main scripts:

1. **main.py** – Core data processing and analysis pipeline  
2. **extra_metrics.py** – Additional performance and error metrics  
3. **nyc_bound.py** – Generates a scatterplot within NYC geographic boundaries  

## Prerequisites

- **Python 3.7** or higher  
- Required Python packages (install via pip):  
  - pandas  
  - numpy  
  - matplotlib  
  - geopandas  
  - shapely  
  - scikit-learn  

## Project Structure
/your-project-folder
├── main.py
├── extra_metrics.py
├── nyc_bound.py
├── data/         
├── outputs/           
└── README.md

## Usage
1. Run the main pipeline: ***"python main.py"*** -
   - Ingests raw data, performs cleaning, modeling, and saves primary outputs.
2. Compute extra metrics: ***"python extra_metrics.py"*** -
   - Calculates additional performance metrics and error analysis based on the outputs from main.py.
3. Generate NYC scatterplot: ***"python nyc_bound.py"*** -
   - Uses GeoPandas to load the NYC boundary shapefile and overlays scatter data points.
   - Saves the figure as nyc_scatterplot.png in the working directory.

## Notes
> Ensure that all input data files are located in the paths expected by each script (check configuration within each script).
> You can customize file paths and parameters by editing the configuration section at the top of each script.
> For any issues or questions, please refer to the inline documentation in each Python file.
