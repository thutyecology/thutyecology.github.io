---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

A 30 m annual cropland dataset of China from 1986 to 2021 (CACD)
=====

The dataset was produced by using numerous Landsat satellite images on the cloud computing platform of [Google Earth Engine](https://earthengine.google.com/){:target="_blank"}. First, training samples were collected based on prerequisite knowledge, existing land cover baseline maps, and a time-weighted dynamic time warping method. Second, multi-year phenological features derived from time-series Landsat imagery were fed into a random forest classifier to obtain per-pixel annual cropland probabilities. Third, the [LandTrendr](https://emapr.github.io/LT-GEE/landtrendr.html){:target="_blank"} change detection algorithm was employed to classify the cropland probability time series into several segments, in which breakpoints and corresponding years of changes were recorded. Fourth, annual cropland types were identified from the LandTrendr segmentation results based on the established discrimination rules. Finally, post-classification processing was applied to better refine cropland maps.

* Download URL: https://zenodo.org/records/7936885
* Data format: .tif
* Pixel size: 30 m
* Projection: EPSG: 4326 (WGS84)
* Values: 1 denotes cropland and 0 denotes non-cropland

For more information on CACD, please refer to our accompanied paper at https://doi.org/10.5194/essd-2023-190

How to cite. **Ying Tu**, Shengbiao Wu, Bin Chen, Qihao Weng, Peng Gong, Yuqi Bai, Jun Yang, Le Yu, and Bing Xu\*. [A 30 m annual cropland dataset of China from 1986 to 2021](https://doi.org/10.5194/essd-2023-190){:target="_blank"}. *Earth System Science Data*. (Under review).


More updates soon
------
