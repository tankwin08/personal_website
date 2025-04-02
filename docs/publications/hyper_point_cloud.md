---
date: "2018-12-13"

description: A new way to visualiza and analyze waveform lidar by converting them into the traditional lidar format (point cloud).

fact: Interesting little tidbit shown below image on summary and detail page
featured: true
image: /img/HPC.png
link: https://www.mdpi.com/2072-4292/10/12/1949
pubtype: Paper
sitemap:
  priority: 0.8
tags:
- hyper point cloud (HPC)
- HPC-based intensity surface
- gridding
- tree segmentation
- vegetation structure
 
title: 'From LiDARWaveforms to Hyper Point Clouds: A Novel Data Product to Characterize Vegetation Structure'

weight: 400
---


**Introduction:**

Full waveform (FW) LiDAR holds great potential for retrieving vegetation structure parameters at a high level of detail, but this prospect is constrained by practical factors such as the lack of available handy processing tools and the technical intricacy of waveform processing.

**Methods:**

This study introduces a new product named the Hyper Point Cloud (HPC), derived from FW LiDAR data, and explores its potential applications, such as tree crown delineation using the HPC-based intensity and percentile height (PH) surfaces, which shows promise as a solution to the constraints of using FW LiDAR data.



**Highlight:**

(1) why named hyper point cloud? 

The results of the HPC present a new direction for handling FW LiDAR
data and offer prospects for studying the mid-story and understory of vegetation with high point
density (~182 points/m2).

(2) what HPC can do?

The intensity-derived digital surface model (DSM) generated from the
HPC shows that the ground region has higher maximum intensity (MAXI) and mean intensity (MI) than the vegetation region, while having lower total intensity (TI) and number of intensities (NI) at a given grid cell.


(3) why contour of intensity can work for tree segmentation?


Our analysis of intensity distribution contours at the individual tree level exhibit similar patterns, indicating that the MAXI and MI decrease from the tree crown center to the tree boundary, while a rising trend is observed for TI and NI. 

These intensity variable contours provide a theoretical justification for using HPC-based intensity surfaces to segment tree crowns and exploit their potential for extracting tree attributes. The HPC-based intensity surfaces and the HPC-based PH Canopy Height Models (CHM) demonstrate promising tree segmentation results comparable to the LiDAR-derived CHM for estimating tree attributes such as tree locations, crown widths and tree heights.


We envision that products such as the HPC and the HPC-based intensity and height surfaces introduced in this study can open new perspectives for the use of FW LiDAR data and alleviate the technical barrier of exploring FW LiDAR data for detailed vegetation structure characterization.
