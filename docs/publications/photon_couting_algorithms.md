---
date: "2018-02-13"

description: This study is mainly to demonstrat how to process ATL03 data of ICESat-2 to ATL08 data using the adaptive framework. (1) An adaptive methodological framework was developed to process upcoming ICESat-2 data. (2) Basic algorithms for ground and canopy photon classification with ICESat-2-like data. (3) Terrain and canopy height measurements with MABEL and simulated ICESat-2 data. 

fact: Interesting little tidbit shown below image on summary and detail page
featured: true
image: /img/photon_counting_processing.png
link: https://www.mdpi.com/2072-4292/10/1/39
pubtype: Paper
sitemap:
  priority: 0.8
tags:
- ICESat-2
- ATL03, ATL08
- Photon classification
- Photon counting LiDAR
- ATLAS
- MABEL
- Canopy height
- Terrain elevation 
title: 'Photon counting LiDAR: An adaptive ground and canopy height retrieval
algorithm for ICESat-2 data'
weight: 400
---


**Introduction:**

The upcoming Ice, Cloud and Land Elevation Satellite-2 (ICESat-2) mission will offer prospects for mapping and monitoring biomass and carbon of terrestrial ecosystems over large areas using photon counting LiDAR data

**Goal:**

We aim to develop a methodology to derive terrain elevation and vegetation canopy height from testbed sensor data and further pre-validate the capacity of the mission to meet its science objectives for the ecosystem community.

**Methods:**

We investigated a novel methodological framework with two essential steps for characterizing terrain and canopy height using Multiple Altimeter Beam Experimental LiDAR (MABEL) data and simulated ICESat-2 data with various vegetation conditions. Our algorithm first implements a multi-level noise filtering approach to minimize noise photons and subsequently classifies the remaining photons into ground and top of canopy using an overlapping moving window method and cubic spline interpolation.


**Highlight:**

(1) Noise filtering: 

Results of noise filtering show that the design of the multi-level filtering process is effective to identify background noise and preserve
signal photons in the raw data. 

(2) Day time vs. night time

Moreover, calibration results using MABEL and simulated ICESat-2 data share
similar trends with the retrieved terrain being more accurate than the retrieved canopy height, and the nighttime results being better than corresponding daytime results.


(3) Simulated ICESat-2 vs. MABEL

Compared to the results of simulated ICESat-2 data,
MABEL data achieve lower accuracy for ground and canopy heights in terms of root mean square error (RMSE), which may partly result from the inconsistency between MABEL and reference data. Specifically, simulated
ICESat-2 data using 115 various nighttime and daytime scenarios, yield average RMSE values of 1.83m and 2.80m for estimated ground elevation, and 2.70m and 3.59m for estimated canopy height.

(4) Percentile height validation
Additionally, the accuracy assessment of percentile heights of simulated ICESat-2 data further substantiates the robustness of the methodology from different perspectives. 

The methodology developed in this study illustrates plausible ways of processing the data that are structurally similar to expected ICESat-2 data and holds the potential to be a benchmark for further method adjustment once genuine ICESat-2 are available.


