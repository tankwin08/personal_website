---
date: "2019-12-08"

description: Applied Segnet method to count the number of sogrhum panicles.

fact: Interesting little tidbit shown below image on summary and detail page
featured: true
image: /img/deep_learning_count.png
link: https://www.mdpi.com/2072-4292/11/24/2939
pubtype: Paper
sitemap:
  priority: 0.9
tags:
- deep learning
- semantic segmentation
- sorghum panicle
- plant phenotyping
- unmanned aerial systems (UAS)
- plant breeding
- automation
- counting

title: 'A Deep Learning Semantic Segmentation-Based Approach for Field-Level Sorghum Panicle Counting'
weight: 400
---


**Introduction:**

Small unmanned aerial systems (UAS) have emerged as high-throughput platforms for the collection of high-resolution image data over large crop fields to support precision agriculture and plant breeding research. At the same time, the improved efficiency in image capture is leading to massive datasets, which pose analysis challenges in providing needed phenotypic data.


To complement these high-throughput platforms, there is an increasing need in crop improvement to develop robust image analysis methods to analyze large amount of image data. Analysis approaches based on deep learning models are currently the most promising and show unparalleled performance in analyzing large image datasets.

**Goal:**

This study developed and applied an image analysis approach based on a
SegNet deep learning semantic segmentation model to estimate sorghum panicles counts, which are critical phenotypic data in sorghum crop improvement, from UAS images over selected sorghum experimental plots.

**Methods:**

The SegNet model was trained to semantically segment UAS images into sorghum
panicles, foliage and the exposed ground using 462, 250 * 250 labeled images, which was then applied to field orthomosaic to generate a field-level semantic segmentation.


**Highlights:**

(1) post processing

Individual panicle locations were obtained after post-processing the segmentation output to remove small objects and split merged panicles. A comparison between model panicle count estimates and manually digitized panicle locations in 60 randomly selected plots showed an overall detection accuracy of 94%. 

(2) plot level

A per-plot panicle count comparison also showed high agreement between estimated and reference panicle counts (Spearman correlation r = 0.88, mean bias = 0.65).

(3) where is the error coming from?

Misclassifications of panicles during the semantic segmentation step and mosaicking errors in the field orthomosaic contributed mainly to panicle detection errors.


Overall, the approach based on deep learning semantic segmentation showed good promise and with a larger labeled dataset and extensive hyper-parameter tuning, should provide even more robust and effective characterization of sorghum panicle counts. 





