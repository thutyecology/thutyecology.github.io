---
layout: archive
permalink: /research/methods/cacd/
author_profile: false
title: Mapping Annual Cropland Dynamics in China
---

Accurate, detailed, and up-to-date information on cropland extent is crucial for provisioning food security and environmental sustainability. However, because of the complexity of agricultural landscapes and lack of sufficient training samples, it remains challenging to monitor cropland dynamics at high spatial and temporal resolutions across large geographical extents, especially for regions where agricultural land use is changing dramatically. Here we developed a cost-effective annual cropland mapping framework that integrated time-series Landsat satellite imagery, automated training sample generation, as well as machine learning and change detection techniques. We implemented the proposed scheme to a cloud computing platform of Google Earth Engine and generated a novel dataset of China's annual cropland at a 30 m spatial resolution (namely CACD). Results demonstrated that our approach was capable of tracking dynamic cropland changes in different agricultural zones. The pixel-wise F1 scores for annual maps and change maps of CACD were 0.79 ± 0.02 and 0.81, respectively. Further cross-product comparisons, including accuracy assessment, correlations with statistics, and spatial details, highlighted the precision and robustness of CACD compared with other datasets. According to our estimation, from 1986 to 2021, China's total cropland area expanded by 30 300 km2 (1.79 %), which underwent an increase before 2002 but a general decline between 2002 and 2015, and a slight recovery afterward. Cropland expansion was concentrated in the northwest while the eastern, central, and southern regions experienced substantial cropland loss. In addition, we observed 419 342 km2 (17.57 %) of croplands that were abandoned at least once during the study period. The consistent, high-resolution data of CACD can support progress toward sustainable agricultural use and food production in various research applications. The full archive of CACD is freely available at https://doi.org/10.5281/zenodo.7936885.

![](https://thutyecology.github.io/images/cacd-flowchart.png){:height="150px" width="600px"}

Flowchart of this study for mapping annual cropland dynamics.


![](https://thutyecology.github.io/images/cacd1.png){:height="150px" width="600px"}

Spatial agreement of cropland extent of the five products (CACD, CLCD, CLUD, GLAD, and GFSAD) in 2015. Matched level indicates how often a pixel is identified as cropland. For example, “4” means four out of the five products recognize it as cropland. The bar chart in the lower-left corner denotes the area proportion of different matched levels (1–5).


![](https://thutyecology.github.io/images/cacd2.png){:height="150px" width="600px"}

Regional comparisons of the five products in 2015. CACD outperforms other products in terms of classification accuracy and spatial details.


![](https://thutyecology.github.io/images/cacd3.png){:height="150px" width="600px"}

Examples of cropland expansion and loss between 1986 and 2021 in four selected regions in China: (a) Chifeng, Inner Mongolia, where large-scale cropland expansion occurred after 2006 for pasture cultivation; (b) Aksu, Xinjiang, which was mainly dominated by cotton cultivation; (c) Shanghai, where rapid urbanization induced extensive cropland loss; and (d) Tongren, Guizhou, where some croplands in the mountainous area had been abandoned due to soil infertile and rural out-migration.


Our results revealed that 419342 km2 (17.57 %) of the croplands in China have been abandoned at least once during the past decades. Most abandoned croplands have been distributed in the central and the western regions (from 100 to 125° E and from 20 to 50° N), particularly in Inner Mongolia, Gansu, Shaanxi, and Yunan provinces. This spatial pattern is consistent with that of Li et al. (2018), who estimated the extent of cropland abandonment in China's mountainous regions using multiple regression models. The average altitude of abandoned cropland is 860 m, 81 % of which is in regions below 1500 m. Temporally, the annual cropland abandonment area in China showed an upward trend from 1990 to 2015, i.e., it increased from 7516 to 14823 km2.

![](https://thutyecology.github.io/images/cacd-abandon.png){:height="150px" width="600px"}

Cropland abandonment in China between 1990 and 2015. (a) Spatial distribution of abandonment time. (b) Histogram distribution within different elevation ranges. (c) Annual trends of abandonment area.


Reference: Ying Tu, Shengbiao Wu, Bin Chen, Qihao Weng, Yuqi Bai, Jun Yang, Le Yu, and Bing Xu\*. [A 30 m annual cropland dataset of China from 1986 to 2021](https://essd.copernicus.org/articles/16/2297/2024/essd-16-2297-2024.html){:target="_blank"}. *Earth System Science Data*. (2024): 2297-2316.
    
