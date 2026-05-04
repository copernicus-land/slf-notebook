# slf-notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/copernicus-land/slf-notebook/blob/main/zonal_temporal_stats_v6.ipynb)


This repository contains a Jupyter notebook that processes Small Landscape Features (SLF) data from the Copernicus Land Monitoring Service (CLMS) to compute zonal and temporal statistics over selected areas of interest. 
At the moment, it is adjusted to run on Google Colab.

The notebook guides you through three self-contained geospatial workflows: 

- A: Agriculture - monitoring crop/land indicators per parcel across years
- B: Biodiversity - aggregating habitat indicators at admin level
- C: Urban - tracking tree canopy extent

**Each use case follows the same workflow:** 

1. Load & visualise data 
2. Select Areas of Interest interactively 
3. Run zonal statistics (2018 & 2021) 
4. Compute change metrics 
5. Visualise results (maps + charts) 
6. Export outputs (CSV + GeoJSON)