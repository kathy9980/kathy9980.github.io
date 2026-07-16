---
title: "Research Overview"
permalink: /research/
author_profile: true
---

My research focuses on satellite remote sensing, time-series analysis, and geospatial artificial intelligence (GeoAI) to investigate forest disturbance, resilience, and ecosystem dynamics under environmental change. I integrate multi-sensor satellite data fusion, dense time-series modeling, and explainable machine learning to extract reliable and interpretable signals from large-scale Earth observation datasets.

## Key Research Themes

### Multi-sensor Satellite Data Fusion for Advanced Land Monitoring

I developed the **Time-series-based Image Fusion (TIF)** algorithm to harmonize Landsat and Sentinel-2 imagery into a dense 10-m optical time series. This work has been published in *[Remote Sensing of Environment](https://doi.org/10.1016/j.rse.2025.115035)* and is being integrated into NASA's Harmonized Landsat and Sentinel-2 (HLS) pipeline. This work enables high-resolution monitoring of land changes, such as insect disturbance detection, crop phenology monitoring, and flash flood mapping.

<div align="center">
  <img src="/images/tif-figure2.jpg" style="width:80%;">
  <p><em><strong>Fig. 1.</strong> Workflow of the Time-series-based Image Fusion (TIF) algorithm.</em></p>
</div>

<div align="center">
  <img src="/images/TIF_results.png" style="width:80%;">
  <p><em><strong>Fig. 2.</strong> Comparison of change maps generated from Sentinel-2 (S10, reference), TIF (our approach), and other image fusion and resampling methods. Gray indicates stable surfaces, white indicates detected changes, and black represents invalid pixels masked by the QA band. The yellow circle highlights a land cover conversion from forest to bare land.</em></p>
</div>

---

### Global Forest Resilience and Disturbance Analysis

My work evaluates the reliability of satellite-derived resilience indicators for large-scale ecosystem stability analysis, with a particular focus on understanding forest health and resilience under diverse natural and anthropogenic stressors.

<div align="center" style="display:flex; gap:20px; justify-content:center; align-items:flex-start;">

  <div style="flex:1; text-align:center;">
    <img src="/images/DOY_Animation_ROI00.gif" style="width:100%;">
    <p><strong>Disturbance Timing</strong></p>
  </div>

  <div style="flex:1; text-align:center;">
    <img src="/images/MAG_Animation_ROI00.gif" style="width:100%;">
    <p><strong>Disturbance Severity</strong></p>
  </div>

</div>

<p align="center"><em><strong>Fig. 3.</strong> Spongy moth outbreak detected from 10-m Harmonized Landsat and Sentinel-2 imagery (Song <em>et al.</em>, 2025). Left: disturbance timing inferred from the detected disturbance onset. Right: disturbance severity represented by the detected disturbance magnitude.</em></p>

---

### GeoAI, Explainable Machine Learning, and Causal Inference

I apply machine learning models, together with explainability methods (e.g., SHAP and LIME) and causal inference frameworks, to identify the key drivers of global forest resilience change while improving the interpretability and transparency of data-driven ecosystem studies.

---

### Vegetation Risk and Infrastructure Vulnerability Assessment

In collaboration with the [StormWise](https://stormwise.uconn.edu/) program and the Eversource Energy Center, I developed machine learning models that integrate satellite, aerial, LiDAR, and infrastructure data to quantify vegetation-related power outage risks. This work translates environmental monitoring into actionable insights for utility vegetation management and community-level storm damage mitigation.

<div align="center">
  <a href="https://dynamic-amulet-244714.projects.earthengine.app/view/tree-failure-risk-map-site-01" target="_blank">
    <img src="/images/Eversource-GEE-fig.png" style="width:80%;">
  </a>
  <p><em><strong>Fig. 4.</strong> Predicted roadside tree failure risk map. Click the figure to explore the interactive Google Earth Engine application.</em></p>
</div>
