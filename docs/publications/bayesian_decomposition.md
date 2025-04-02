---
date: "2017-08-08"
description: To better understand the uncertainty of our waveform processing, a Bayesian method was introduced to assess different methods' performance for waveform lidar processing. The methods have been summarized into an R package named wavefromlidar which is available in CRAN https://github.com/tankwin08/waveformlidar.
fact: Interesting little tidbit shown below image on summary and detail page
featured: true
image: /img/bayesian_uncertainty.jpg
link: https://www.researchgate.net/publication/319018940_Bayesian_decomposition_of_full_waveform_LiDAR_data_with_uncertainty_analysis
pubtype: Paper
sitemap:
  priority: 0.8
tags:
- algorithm development
- Waveform LiDAR
- Bayesian inference
- Tree canopy height
- Model reasonableness
- Decomposition
- Uncertainty
title: 'Bayesian decomposition of full waveform LiDAR data with uncertainty
analysis'
weight: 400
---


**Introduction:**

A thorough understanding of full waveform (FW) LiDAR data processing and associated uncertainty is critical to vegetation applications such as retrieving forest structure variables and estimating forest biomass.

**Goal:**

To qunaitfy the uncertaitny of the estimation and gain a deep understanding of waveform lidar processing. 


**Methods:**

This paper applies the Bayesian non-linear modeling concept to process small-footprint FW LiDAR data (the Bayesian decomposition) collected at a study site of the National Ecological Observatory Network (NEON) to investigate its potential for waveform decomposition and uncertainty estimation.

Specifically, several possible models suitable for fitting waveforms were assessed within the Bayesian framework, and the Gaussian model was selected to
perform the Bayesian decomposition. Subsequently, we conducted performance evaluation and uncertainty analysis at the parameter, derived point cloud and surface model levels.
 

**Highlights:**

(1) which model to use?

Results of the model reasonableness show that the Gaussian model is superior to alternative models with respect to uncertainty, physical meaning
and processing efficiency. 

(2) How the Bayesiand decomposition perform?

After converting waveforms to discrete points, the model comparisons demonstrate
that the Bayesian decomposition can be utilized for FW LiDAR data processing, and its results are comparable to the direct decomposition (DD), Gold and RL (Richardson-Lucy) approaches in terms of the root mean squared error (RMSE < 0.93 m) of the point distances between the waveform-based point cloud and the reference point cloud. 

(3) which part of vegetation have evident advantage for waveform lidar?

Additionally, more points can be extracted from FW LiDAR data with these methods than discrete-return LiDAR data, especially at the mid-story of vegetation based on the results of height bins, percentile heights and canopy LiDAR density at the individual tree level. 

(4) Uncertainy analysis

Moreover, uncertainty estimates from the Bayesian method enhance the credibility of decomposition results in a probabilistic sense to capture the true error of estimates and trace the uncertainty propagation along the processing steps. For example, results of the surface model yield larger RMSE values (1.38 m vs. 0.65 m) with a wider credible interval than quantile point clouds with a more
compact distribution.

**advantages of Bayesian**

In contrast to commonly used deterministic approaches, the Bayesian decomposition
method can produce an ensemble of reasonable parameter estimates with probability through Markov Chain Monte Carlo (MCMC) sampling from the posterior distribution of model parameters. 

These parameter estimates and corresponding derived products can be queried to provide **meaningful interpretation of results** and associated uncertainty. Both the flat priors and empirical priors can achieve good performance of the decomposition while the empirical priors tend to significantly speed up the model convergence


This study provides an alternative and innovative approach for waveform processing that willbenefit high fidelity processing of waveform LiDAR data to characterize vegetation structures. 




