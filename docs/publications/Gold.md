---
date: "2017-04-08"
description: This paper introduced a novel way to process full waveformlidar data and compared it with exisiting methods such as decompostion and RL deconvolution methods to further show the advantages of new method. These methods have been summarized into an R package named wavefromlidar which is available in CRAN https://github.com/tankwin08/waveformlidar.
fact: Interesting little tidbit shown below image on summary and detail page
featured: true
image: /img/gold.png
link: https://www.researchgate.net/publication/316846371_Zhou_T_SC_Popescu_K_Krause_RD_Sheridan_and_E_Putman_2017_Gold_-_A_novel_deconvolution_algorithm_with_optimization_for_waveform_LiDAR_processing_ISPRS_Journal_of_Photogrammetry_and_Remote_Sensing_12920
pubtype: Paper
sitemap:
  priority: 0.8
tags:
- algorithm development
- Waveform LiDAR
- Deconvolution
- Gold
- Richardson-Lucy (RL)
- Decomposition
- Parameter uncertainty
title: 'Gold-A novel deconvolution algorithm with optimization for waveform LiDAR processing'
weight: 400
---


**Introduction:**

Waveform Light Detection and Ranging (LiDAR) data have advantages over discrete-return LiDAR data inaccurately characterizing vegetation structure. However, we lack a comprehensive understanding ofwaveform data processing approaches under different topography and vegetation conditions. 

**Goal:**

The objec-tive of this paper is to highlight a novel deconvolution algorithm, the Gold algorithm, for processingwaveform LiDAR data with optimal deconvolution parameters. Further, we present a comparative studyof waveform processing methods to provide insight into selecting an approach for a given combination ofvegetation and terrain characteristics. 

**Methods:**

We employed two waveform processing methods: 

(1) direct decomposition, 

(2) deconvolution and decomposition. 

In method (2), we utilized two deconvolutionalgorithms - the Richardson-Lucy (RL) algorithm and the Gold algorithm. 

The comprehensive and quan-titative comparisons were conducted in terms of the number of detected echoes, position accuracy, thebias of the end products (such as digital terrain model (DTM) and canopy height model (CHM)) fromthe corresponding reference data, along with parameter uncertainty for these end products obtainedfrom different methods. 

Where:

This study was conducted at three study sites that include diverse ecological regions, vegetation and elevation gradients. 

**Highlights:**

(1) Results demonstrate that two deconvolution algorithms **are sensitive** to the pre-processing steps of input data. The deconvolution and decomposition methodis more capable of detecting hidden echoes with a lower false echo detection rate, especially for theGold algorithm. 

(2) Compared to the reference data, all approaches generate satisfactory accuracy assess-ment results with small mean spatial difference (<1.22 m for DTMs, <0.77 m for CHMs) and root meansquare error (RMSE) (<1.26 m for DTMs, <1.93 m for CHMs). **More specifically**, the Gold algorithm is **supe-rior to** others with smaller root mean square error (RMSE) (<1.01 m), while the direct decompositionapproach works better in terms of the percentage of spatial difference within 0.5 and 1 m.

(3) The parameteruncertainty analysis demonstrates that the Gold algorithm outperforms other approaches in dense veg-etation areas, with the smallest RMSE, and the RL algorithm performs better in sparse vegetation areas interms of RMSE. 

(4) Additionally, the high level of uncertainty occurs more on areas with high slope and highvegetation. 

This study provides an alternative and innovative approach for waveform processing that willbenefit high fidelity processing of waveform LiDAR data to characterize vegetation structures. 



{{< youtube id="A4MWxAkolO4" t="80" width="300px" >}}
