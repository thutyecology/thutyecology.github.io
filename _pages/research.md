---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

--------------------------------------------------

Mapping Essential Urban Land Use Categories (EULUC)
======

**Introduction**

Land use serves as a reflection of human activities on Earth, with urban land use standing out as the most prominent manifestation of human alteration. Due to population growth and urbanization, urban land use is changing dynamically in recent years. However, our understanding of the distribution, patterns, and composition of various land use types in urban areas is hampered by limitations in data sources, methodologies, and classification schemes used in existing maps. Addressing these issues, here, we carried out a series of studies under the **Essential Urban Land Use Categories (EULUC)** framework that aims to provide accurate, detailed, and high-resolution land use maps for Chinese and US cities.


**1. EULUC-China**
------

In this research, we report a new urban land use map for China that uses 10-m satellite images, OpenStreetMap, nighttime lights, POI, and Tencent social big data all in 2018 as input features. Training and validation samples are separately collected through a crowdsourcing approach involving 21 research groups in 27 selected representative cities. We apply the training parcels with the extracted features acquired in 2018 to produce a parcel-level mapping of EULUC-China with the random forest classifier. The overall accuracy of the EULUC-China map evaluated against the independent validation sample is 61.2% for Level I and 57.5% for Level II. The results presented here mark the beginning of a new way of collaborative urban land use mapping over large areas, that is a central data processing with crowdsourced collection of training and validation samples.

![](https://thutyecology.github.io/images/euluc-china.png){:height="150px" width="600px"}

Map of Essential Urban Land Use Categories in China (EULUC-China) in 2018

Reference: Peng Gong, et al. [Mapping essential urban land use categories in China (EULUC-China): preliminary results for 2018.](https://doi.org/10.1016/j.scib.2019.12.007){:target="_blank"} *Science Bulletin* 65, no. 3 (2020): 182-187.


**2. EULUC-seg**
------

Understanding distributions of urban land use is of great importance for urban planning, decision support, and resource allocation. Based on the EULUC framework, we further proposed a segmentation-based framework named EULUC-seg to improve the mapping results of EULUC at the city scale. An object-based segmentation approach was first applied to generate the basic mapping units within urban parcels. Multiple features derived from high-resolution remotely sensed and social sensing data were updated and then recalculated within each unit. Random forest was adopted as the machine learning algorithm for classifying urban land use into five Level I classes and twelve Level II classes. Finally, an accuracy assessment was carried out based on a collection of manually interpreted samples. Results showed that our derived map achieved an overall accuracy of 87.58% for Level I, and 73.53% for Level II. The accurate and refined map of EULUC-seg is expected to better support various applications in the future.

<!--![](https://thutyecology.github.io/images/euluc-seg.png)

Comparison of remotely sensed images and urban land use mapping results. (a–c) The central urban area of Ningbo. (d–f) A suburb located 10 km northwest of the central city. (g–i) The Yuyao county located 40 km west of the central city. Three columns from left to right denote the Sentinel-2 optical imagery (false color composition), maps of EULUC [1], and maps of EULUC-seg implemented in this study, respectively.

Workflow of the proposed mapping scheme.
-->
<iframe
    src="https://thutyecology.users.earthengine.app/view/euluc-ningbo-viewer"
    width = "960"
    height = "500"
    frameborder="0"
    allowfullscreen>
</iframe>

Reference: Ying Tu, Bin Chen, Tao Zhang, and Bing Xu. [Regional Mapping of Essential Urban Land Use Categories in China: A Segmentation-Based Approach.](https://www.mdpi.com/2072-4292/12/7/1058){:target="_blank"} *Remote Sensing* 12, no. 7 (2020): 1058.


**3. EULUC-composited**
------

Detailed information on urban land uses has been an essential requirement for urban land management and policymaking. Recent advances in remote sensing and machine learning technologies have contributed to the mapping and monitoring of multi-scale urban land uses, yet there lacks a holistic mapping framework that is compatible with different end users’ demands. Moreover, land use mix has evolved to be a key component in modern urban settings, but few have explicitly measured the spatial complexity of land use or quantitively uncovered its driving forces. Addressing these challenges, here we developed a novel **two-stage bottom-up scheme** for mapping essential urban land use categories. In the first stage, we conducted object-based land use classification using crowdsourcing features derived from multi-source open big data and an automated ensemble learning approach. In the second stage, we identified parcel-based land use attributes, including the dominant type and mixture mode, by spatially correlating land parcels with the object-based results. Furthermore, we investigated the potential influencing factors of land use mix using principal components analysis and multiple linear regression.

![](https://thutyecology.github.io/images/euluc-composited-1.png){:height="150px" width="600px"}

Flowchart of the proposed two-stage urban land use mapping scheme.

Experimental results in Ningbo, a coastal city in China, showed that the proposed framework could accurately depict the distribution and composition of urban land uses. At the object scale, the highest classification accuracy was as high as 86% and 78% for the major (Level I) and minor (Level II) categories, respectively. At the parcel scale, the generated land use maps were spatially consistent with the object-based maps. We found larger parcels were more likely to be mixed in land use, and industrial lands were characterized as the most complicated category. We also identified multiple factors that had a collective impact on land use mix, including geography, socioeconomy, accessibility, and landscape metrics. Altogether, our proposed framework offered an alternative to investigating urban land use composition, which could be applied in a broad range of implications in future urban studies.
 
![](https://thutyecology.github.io/images/euluc-composited-2.png)

Land use mix of Level I categories in Ningbo city. (a) Maps of complexity index in the city center. (b) Maps of dominant rate in the city center. (c) The relationship between complexity index and area of parcels. (d) The relationship between dominant rate and area of parcels. r in (c,d) represents the Pearson correlation coefficient.

Reference: Ying Tu, Bin Chen, Wei Lang, Tingting Chen, Miao Li, Tao Zhang, and Bing Xu. [Uncovering the Nature of Urban Land Use Composition Using Multi-source Open Big Data with Ensemble Learning.](https://www.mdpi.com/2072-4292/13/21/4241){:target="_blank"} *Remote Sensing* 13, no. 21 (2021): 4241.

    
**4. EULUC-USA**
------

Urban land-use maps outlining the distribution, pattern, and composition of various land use types are critically important for urban planning, environmental management, disaster control, health protection, and biodiversity conservation. Recent advances in remote sensing and social sensing data and methods have shown great potentials in mapping urban land use categories, but they are still constrained by mixed land uses, limited predictors, non-localized models, and often relatively low accuracies. To inform these issues, we proposed a robust and cost-effective framework for mapping urban land use categories using openly available multi-source geospatial “big data”. With street blocks generated from OpenStreetMap (OSM) data as the minimum classification unit, we integrated an expansive set of multi-scale spatially explicit information on land surface, vertical height, socio-economic attributes, social media, demography, and topography. We further proposed to apply the automatic ensemble learning that leverages a bunch of machine learning algorithms in deriving optimal urban land use classification maps.

![](https://thutyecology.github.io/images/euluc-usa-1.png)

<center>Flowchart of the research data and methods.</center>

Results of block-level urban land use classification in five metropolitan areas of the United States found the overall accuracies of major-class (Level-I) and minor-class (Level-II) classification could be high as 91% and 86%, respectively. A multi-model comparison revealed that for urban land use classification with high-dimensional features, the multi-layer stacking ensemble models achieved better performance than base models such as random forest, extremely randomized trees, LightGBM, CatBoost, and neural networks. We found without very-high-resolution National Agriculture Imagery Program imagery, the classification results derived from Sentinel-1, Sentinel-2, and other open big data based features could achieve plausible overall accuracies of Level-I and Level-II classification at 88% and 81%, respectively. We also found that model transferability depended highly on the heterogeneity in characteristics of different regions. The methods and findings in this study systematically elucidate the role of data sources, classification methods, and feature transferability in block-level land use classifications, which have important implications for mapping multi-scale essential urban land use categories.

![](https://thutyecology.github.io/images/euluc-usa-2.jpeg)

<center>Examples of sampled blocks of different urban land use categories overlaid with Google Earth imagery in Chicago.</center>

Reference: Bin Chen, Ying Tu, Yimeng Song, David M. Theobald, Tao Zhang, Zhehao Ren, Xuecao Li, Jun Yang, Jie Wang, Xi Wang, Peng Gong, Yuqi Bai, and Bing Xu. [Mapping essential urban land use categories with open big data: Results for five metropolitan areas in the United States of America.](https://doi.org/10.1016/j.isprsjprs.2021.06.010){:target="_blank"} *ISPRS Journal of Photogrammetry and Remote Sensing* 178 (2021): 203-218.


More updates soon
------
