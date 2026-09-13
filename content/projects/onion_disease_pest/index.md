---
title: "UAV Multispectral Time-Series and Weather-Based Hurdle Modeling for Onion Diseases and Pest Estimation"
weight: 3
date: 2026-09-13
show_date: false
show_date_updated: false
reading_time: false
share: false

summary: "Developed a multimodal framework combining UAV multispectral imagery, weather data, and machine learning to estimate onion diseases and pest incidence."

tags:
  - Perception & AI
  - UAV Systems

tech_stack:
  - Python
  - UAV Multispectral Imaging
  - Machine Learning
  - Time-Series Analysis
  - Vegetation Indices
  - Feature Engineering
  - Random Forest
  - SVM
  - Data Fusion

links:
  - type: pdf
    url: uploads/onion-disease-pest-estimation-paper.pdf
    label: "Paper"

  - type: pdf
    url: uploads/onion-disease-pest-estimation-poster.pdf
    label: "Poster"

featured: true
---

<p align="justify">
This work presents a multimodal framework for estimating major onion
diseases and pests by combining UAV-based multispectral imagery with
ground-based weather data. The study was conducted on Bhima onion
under naturally varying, co-occurring stress conditions, focusing on
stemphylium blight, anthracnose, purple blotch, and thrips.
</p>

<p align="justify">
Eleven field trials were conducted at the ICAR–Directorate of Onion &
Garlic Research (DOGR), Maharashtra, between August 2023 and March 2024.
Multispectral data were acquired using a MicaSense RedEdge-P mounted on
a quadcopter, while an IoT-based weather station continuously recorded
environmental conditions. UAV imagery was processed into aligned and
radiometrically calibrated multispectral orthomosaics for region-wise
vegetation-index analysis.
</p>

<figure>
    <img src="featured.png"
         alt="UAV multispectral and weather-based onion stress estimation framework">
    <figcaption>
        Figure: UAV multispectral and weather-based framework for onion disease and pest estimation
    </figcaption>
</figure>

<p align="justify">
Fourteen vegetation indices were evaluated together with meteorological
variables. To capture crop-stress dynamics beyond static spectral
measurements, I worked with temporal features including first- and
second-order changes and lagged observations, along with
biomass-normalized ratio and difference features.
</p>

<p align="justify">
The analysis revealed a biomass-related confounding effect in the
relationship between conventional vegetation indices and disease
severity. Feature engineering using temporal changes and
biomass-normalized measurements helped isolate physiological stress
signals from changes in canopy biomass.
</p>

<p align="justify">
A Green Stress Ratio (GSR) was introduced as a new vegetation index and
showed the strongest associations across the evaluated disease and pest
categories. The final framework combined multispectral and
meteorological features with a two-stage hurdle model: a classification
stage for detecting stress presence followed by a regression stage for
estimating stress severity.
</p>

<p align="justify">
Random Forest, SVM/SVR, and linear models were evaluated using
trial-independent validation. The Random Forest hurdle model provided
the most consistent overall performance, with particularly strong
detection results for purple blotch and stemphylium blight. The study
demonstrates the potential of combining UAV sensing, environmental
measurements, and machine learning for scalable crop-health monitoring
and precision agriculture.
</p>
