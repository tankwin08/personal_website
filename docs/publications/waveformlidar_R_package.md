---
date: "2019-10-31"

description: The brief introduction of waveformlidar package and the specific usages and corresponding logic.Examples of how to use them can be found in https://github.com/tankwin08/waveformlidar/tree/master/vignettes

fact: Interesting little tidbit shown below image on summary and detail page
featured: true
image: /img/r_package_graphic_abstract1.png
link: https://www.mdpi.com/2072-4292/11/21/2552
pubtype: Paper
sitemap:
  priority: 0.8
tags:
- waveform decomposition
- hyper point cloud
- deconvolution
- Waveform signatures
- waveform gridding & voxel
- composite waveform
title: 'waveformlidar: An R Package for Waveform LiDAR Processing and Analysis'
weight: 400
---


**Introduction:**

A wealth of FullWaveform (FW) LiDAR (Light Detection and Ranging) data are available to the public from different sources, which is poised to boost extensive applications of FW LiDAR data. However, we lack a handy and open source tool that can be used by potential users for processing
and analyzing FW LiDAR data. 

**Goal:**
To this end, we introduce waveformlidar, an R package dedicated to
FW LiDAR processing, analysis and visualization as a solution to the constraint.

**What this package provide:**

(1) This package provides several commonly used waveform processing methods such as Gaussian, Adaptive
Gaussian and Weibull decompositions and deconvolution approaches (Gold and Richard-Lucy (RL)) with users' customized settings.

(2) we also developed functions to derive commonly used waveform metrics for characterizing vegetation structure. 

(3) Moreover, a new way to directly visualize FW LiDAR data is developed by converting waveforms into points to form the Hyper Point Cloud (HPC), which can be easily adopted and subsequently analyzed with existing discrete-return LiDAR processing tools such as LAStools and FUSION.

(4) Basic explorations of the HPC such as 3D voxelization of the HPC and conversion from original waveforms to composite waveforms are also available in this package.

All of these functions are developed based on small-footprint FW LiDAR data but they can be easily transplanted to the large footprint FW LiDAR data such as Geoscience Laser Altimeter System (GLAS) and Global Ecosystem Dynamics Investigation (GEDI) data analysis. 


It is anticipated that these functions will facilitate the widespread use of FW LiDAR and be beneficial for better estimating biomass and characterizing vegetation structure at various scales.
