---
date: "2019-01-01"

description: An example of combining ICESat-2 data with landsat to estimate the biomass and forest cover of forest over a regional scale. 

fact: Interesting little tidbit shown below image on summary and detail page
featured: true
image: /img/mapping_biomass_landsat_icesat-2.png
link: https:10.15287/afr.2018.1163

pubtype: Paper
sitemap:
  priority: 0.8
tags:
- ICESat-2
- AGB mapping
- Photon counting lidar
- ATL08
- Canopy cover
- Canopy height
- LandSat
title: 'Mapping forest aboveground biomass with a simulated ICESat-2 vegetation canopy product and Landsat data'
weight: 400
---


**Introduction:**
The assessment of forest aboveground biomass (AGB) can contribute to reducing uncertainties associated with the amount and distribution of terrestrial carbon. The Ice, Cloud and land Elevation Satellite-2 (ICESat-2) was launched on September 15th, 2018 and will provide data which will offer the possibility of assessing AGB and forest carbon at multiple spatial scales.

**Goal:**
The primary goal of this study was to develop an approach for utilizing data similar to ICESat-2's land-vegetation along track product (ATL08) to generate wall-to-wall AGB maps.

**How:**
Utilizing simulated daytime and nighttime ICESat-2 data from planned ICESat-2 tracks over vegetation
conditions in south-east Texas, we investigated the integration of Landsat
data and derived products for AGB model and map production. Linear regression
models were first used to relate simulated photon-counting lidar
(PCL) metrics for 100 m segments along ICESat-2 tracks to reference airborne
lidar-estimated AGB over Sam Houston National Forest (SHNF) in
south-east Texas. Random Forest (RF) was then used to create AGB maps
from predicted AGB estimates and explanatory data consisting of spectral
metrics derived from Landsat TM imagery and land cover and canopy cover
data from the National Land Cover Database (NLCD).

**Highlights:**

Using RF, AGB and AGB uncertainty maps produced at 30 m spatial resolution represented three data scenarios; 

(1) simulated ICESat-2 PCL vegetation product without the
impact of noise (no noise scenario), 

(2) simulated ICESat-2 PCL vegetation
product from data with noise levels associated with daytime operation of
ICESat-2 (daytime scenario), and 

(3) simulated ICESat-2 PCL vegetation
product from data with noise levels associated with nighttime operation of
ICESat-2 (nighttime scenario).


The RF models exhibited moderate accuracies
(0.42 to 0.51) with RMSE values between 19 Mg/ha to 20 Mg/ha with
a separate test set. The adoption of a combinatory approach of simulated
ICESat-2 and Landsat data could be implemented at larger spatial scales and
in doing so, ancillary data such as climatic and topographic variables may
be examined for improving AGB predictions.