---
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research focuses on satellite remote sensing, time-series analysis, and geospatial artificial intelligence (GeoAI) to investigate forest disturbance, resilience, and ecosystem dynamics under environmental change. I integrate multi-sensor satellite data fusion, dense time-series modeling, and explainable machine learning to extract reliable and interpretable signals from large-scale Earth observation datasets.

## Key Research Themes

### Multi-sensor Satellite Data Fusion for Advanced Land Monitoring
I developed the **Time-series-based Image Fusion (TIF)** algorithm to harmonize Landsat and Sentinel-2 imagery into a dense 10-m optical time series. This work has been published in *[Remote Sensing of Environment](https://doi.org/10.1016/j.rse.2025.115035)* and is being integrated into NASA’s Harmonized Landsat and Sentinel-2 (HLS) pipeline. This work enables high-resolution monitoring of land changes, such as insect disturbance detection, crop phenology monitoring, and flash flood mapping. 

<br>
![TIF workflow of 10-m Landsat and Sentinel-2 time series](/images/tif-figure2.jpg){:width="50%"}
<br>
**Fig. 1.** Workflow of the Time-series-based Image Fusion (TIF) algorithm.

<br>
![Study sites for TIF development](/images/TIF_results.png){:width="50%"}
<br>
**Fig. 2.** Study regions used for TIF calibration and validation across the United States. Background: 2021 NLCD land cover.


### Global Forest Resilience and Disturbance Analysis
My work evaluates the reliability of satellite-derived resilience indicators for large-scale ecosystem stability analysis, with a focus on understanding forest health and resilience under diverse natural and anthropogenic stressors.
<div style="display:flex; gap:20px; justify-content:center; align-items:flex-start;">
  <div style="flex:1; text-align:center;">
    <img src="/images/DOY_Animation_ROI00.gif" style="width:100%;">
    <p><b>Disturbance Timing</b></p>
  </div>

  <div style="flex:1; text-align:center;">
    <img src="/images/MAG_Animation_ROI00.gif" style="width:100%;">
    <p><b>Disturbance Severity</b></p>
  </div>
</div>

<p align="center"><em>
**Fig. 3.** Spongy moth outbreak detected from 10-m Harmonized Landsat and Sentinel-2 imagery (Song <em>et al.</em>, 2025). Left: disturbance timing inferred from the detected disturbance onset. Right: disturbance severity represented by the detected disturbance magnitude.
</em></p>
### GeoAI, Explainable Machine Learning, and Causal Inference
I am applying machine learning models, along with explainability tools (e.g., SHAP and LIME), and causal inference frameworks to identify the key drivers of global forest resilience change and to enhance the interpretability and transparency of data-driven ecosystem studies.

### Vegetation Risk and Infrastructure Vulnerability Assessment
In collaboration with the [StormWise](https://stormwise.uconn.edu/) program and the Eversource Energy Center, I developed machine learning (ML) models that integrate satellite, aerial, LiDAR, and infrastructure data to quantify vegetation-related power outage risks. This work translates environmental monitoring into actionable insights for utility vegetation management and community-level storm damage mitigation.

<br>
[![Predicted roadside tree failure risk map](/images/Eversource-GEE-fig.png)](https://dynamic-amulet-244714.projects.earthengine.app/view/tree-failure-risk-map-site-01){:height="85%" width="85%"}
<br>
**Fig. 4.** Predicted roadside tree failure risk GEE map.
