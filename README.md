# Boise-River-SnowMelt

This project analyzes Snow Water Equivalent (SWE) data from the Mores Creek Summit SNOTEL station (station triplet: `637:ID:SNTL`) for a full water year. The goal is to visualize and understand the patterns of snow accumulation and melt within the Boise River Basin.

## Overview

- **Data Source:**  
  SWE data is obtained from the USDA National Water and Climate Center (NWCC) via the AWDB Web Service.
  
- **Analysis Focus:**  
  The project focuses on:
  - Plotting the time series of daily SWE over the water year October 1, 2023 - September 30, 2024.
  - Calculating daily changes in SWE to identify accumulation and melt phases.
  - Exploring cumulative SWE trends over the water year.

## Requirements

- Python 3.x
- [Zeep](https://docs.python-zeep.org/en/master/) for accessing the AWDB Web Service
- [Pandas](https://pandas.pydata.org/) for data manipulation
- [Matplotlib](https://matplotlib.org/) for plotting

You can install the necessary packages using:

```bash
pip install zeep pandas matplotlib
