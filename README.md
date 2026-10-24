# Ahmedabad Urban Climate Analysis

## Overview

A GIS-based assessment of urban expansion and environmental change across
the Ahmedabad Urban Development Authority (AUDA) region, Gujarat, India,
between 2015 and 2025.

## Research Objectives

- Assess changes in built-up land.
- Examine vegetation and land surface temperature patterns.
- Analyse terrain, drainage, rainfall and preliminary flood susceptibility.

## Tools and Data

- Python and Google Colab
- Google Earth Engine and geemap
- GeoPandas, Pandas and Matplotlib
- GIS and remote-sensing datasets (Dynamic World, Sentinel-2, Landsat,
  CHIRPS, NASADEM, MERIT Hydro)
- Satellite-derived and hydroclimatic indicators

## Key Findings

- Built-up land increased by 54.57 km² (13.45%) between 2015 and 2025,
  from 405.77 km² to 460.34 km².
- Vegetation trends showed spatially varied changes.
- Flood susceptibility mapping provided preliminary insights into
  drainage-related risks.

## Repository Contents

- `notebooks/` — analysis notebook
- `results/` — selected maps, charts and animations
- `report/` — project report

## How to Use

1. Open the notebook in Google Colab.
2. Replace `YOUR_GOOGLE_CLOUD_PROJECT_ID` with your own Google Cloud
   project ID and sign in to Google Earth Engine when asked.
3. Upload your own AUDA boundary shapefile when the notebook asks for it.
   The boundary file is not included in this repository.
4. Create a folder named `AUDA_Climate_Portfolio` in your Google Drive,
   where the notebook saves its outputs.
5. Run the cells in order.

## Data sources

All satellite and climate data come from Google Earth Engine:
Dynamic World, Sentinel-2, Landsat, CHIRPS, NASADEM and MERIT Hydro.

## Limitations

The flood-susceptibility map is preliminary. It is a weighted indicator
model and has not been checked against recorded flood events.

## Author

Sadiya Sharmin, Master of Urban Planning, CEPT University
sadiya.sharmin@outlook.com