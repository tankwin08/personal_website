---
date: "2019-11-08"

description: We all know there is information contained in the waveform, how can we extract these information and improved the exsiting applications? The following is an example of the combination of advacned statistcial methods such as Bayesian and Machine learning methods with the waveform signatures for tree species identification using waveform lidar data.

fact: Interesting little tidbit shown below image on summary and detail page
featured: true
image: /img/BAYESIAN_ML_TREE_SPECIES.png
link: https://www.mdpi.com/2072-4292/10/1/39
pubtype: Paper
sitemap:
  priority: 0.9
tags:
- Bayesian multinomial logistic regression
- Conditional inference forests
- Machine learning, Random forests
- Waveform signatures
- Tree segmentation
- Watershed
- composite waveform
title: 'Bayesian and Classical Machine Learning Methods: A Comparison for Tree Species Classification with LiDAR Waveform Signatures'
weight: 400
---


**Introduction:**

A plethora of information contained in full-waveform (FW) Light Detection and Ranging (LiDAR) data offers prospects for characterizing vegetation structures. 

**Goal:**

This study aims to investigate the capacity of FW LiDAR data alone for tree species identification through the integration of waveform metrics with machine learning methods and Bayesian inference.

**Methods:**

Specifically, we first conducted automatic tree segmentation based on the waveform-based canopy height model (CHM) using three approaches including TreeVaW, watershed algorithms and the combination of TreeVaW
and watershed (TW) algorithms. 

Subsequently, the Random forests (RF) and Conditional inference
forests (CF) models were employed to identify important tree-level waveform metrics derived from three distinct sources, such as raw waveforms, composite waveforms, the waveform-based point cloud and the combined variables from these three sources.

Further, we discriminated tree (gray pine, blue oak, interior live oak) and shrub species through the RF, CF and Bayesian multinomial logistic regression (BMLR) using important waveform metrics identified in this study.


**Highlights:**

(1) tree segmentation: 

Results of the tree segmentation demonstrated that the TW algorithms outperformed other algorithms for delineating individual tree crowns. 

(2) RF vs. CF

The CF model overcomes waveform metrics selection bias
caused by the RF model which favors correlated metrics and enhances the accuracy of subsequent classification.

(3) Composite waveform vs. raw waveform

We also found that composite waveforms are more informative than raw waveforms
and waveform-based point cloud for characterizing tree species in our study area.

(4) RF vs. Bayesian 

Both classicalmachine learning methods (the RF and CF) and the BMLR generated satisfactory average overall accuracy (74% for the RF, 77% for the CF and 81% for the BMLR) and the BMLR slightly outperformed the other two methods. 

However, these three methods suffered from low individual classification
accuracy for the blue oak which is prone to being misclassified as the interior live oak due to the similar characteristics of blue oak and interior live oak. 

Uncertainty estimates from the BMLR method compensate for this downside by providing classification results in a probabilistic sense and rendering
users with more confidence in interpreting and applying classification results to real-world tasks such as forest inventory.
 

(5) feature selection:

Overall, this study recommends the CF method for feature selection and
suggests that BMLR could be a superior alternative to classical machining learning methods.






