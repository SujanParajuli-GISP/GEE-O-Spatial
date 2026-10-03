---
date: 2026-09-22
authors:
  - sujan
categories:
  - GeoAI
tags:
  - wildfire
  - machine learning
  - Streamlit
---

# Predicting Next-Day Wildfire Risk from Open Data

An end-to-end pipeline from raw open data to a live alert map.

<!-- more -->

## The pipeline

1. **Ingest** active-fire detections from NASA FIRMS and weather from Meteostat.
2. **Engineer** features per grid cell and day.
3. **Train** a LightGBM model to predict next-day fire risk.
4. **Visualize** alerts in a Streamlit app.

Code: [wildfire-risk-forecast](https://github.com/SujanParajuli-GISP/wildfire-risk-forecast).

!!! note "Starter post"
    This is a starter post. Replace it with your own model metrics, screenshots, and lessons learned.
