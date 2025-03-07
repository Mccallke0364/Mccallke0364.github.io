---
title: "Automated Morphometry" 
date: 2022-10-30
lastmod: 2023-03-12
tags: ["Morphometry","Artificial Intelligence","image annotation","stomata", "leaf"]
author: ["Connor McKeown","Phillip Gillett", "Katherine McCallum", "Dr. Rahul Gomes", "Dr. Nora Mitchell"]
description: "This poster is an overview of automated morphometry research to determine adaptations that plants have made to survive in their environment." 
summary: "Uses AI to label images and determine traits based on stomatal size and field images." 
cover:
    image: "pretty_predicted_mask.png"
    alt: "Image mask based on code"
    relative: false
# editPost:
#     URL: "https://github.com/pmichaillat/hugo-website"
#     Text: "Journal of Oleic Science"

---

---

##### Download
+ [Poster](NCUR_2023_Poplar_Automated_Morphometry_Semifinal_Draft_CURRENT.pdf)
<!-- + [Paper](paper1.pdf)
+ [Online appendix](appendix1.pdf)
+ [Code and data](https://github.com/pmichaillat/feru) -->

---

##### Abstract

A Deep Learning Approach to Automate the Analyses and Prediction of Function for Poplar Stomata 

In plants, stomatal pores regulate the intake of carbon dioxide that enables and powers photosynthesis and the loss of water from the surface of leaves. Variations in stomatal size and density can thus reflect novel strategies that balance water loss with photosynthetic capacity. Poplars are an emerging model system for studying adaptation to climate change in tree species and exhibit variation in stomatal characteristics. Currently, many approaches used in collecting stomatal morphometric data require the manual measurement of microscope images of stomatal imprints by a trained individual using software such as ImageJ. The process can be extensive, inaccurate, and slow down long-awaited results after collection. Our process follows similar methods shown in Gibbs et al. (2021) but differs in the deep learning processes used. This study implements a deep learning method to automate the process of morphometric data collection. Images collected for our approach are accurately labeled using open-source software to identify stomatal pores and guard cells. The preprocessed images along with the generated segmentation masks are fed into the deep learning model. For our study, we will use UNet to segment and measure pixel values that correspond with measurements of stomatal cells and image region properties to measure the stomatal density from prediction. All experiments will be conducted on the University of Wisconsin-Eau Claire BOSE supercomputing cluster. These measurements can be combined with additional climatic data to understand quantitative measures of plant health and viability across geographical and environmental scales.  

---
<!-- 
##### Figure 6: Some Uses For Olive Oil

![](paper1.png)

---

##### Citation

Unterholzer, Detlev A., and  Moritz-Maria von Igelfeld. 2013. "Unusual Uses For Olive Oil." *Journal of Oleic Science* 34 (1): 449–489. http://www.alexandermccallsmith.com/book/unusual-uses-for-olive-oil.

```BibTeX
@article{UI13,
author = {Detlev A. Unterholzer and Moritz-Maria von Igelfeld},
year = {2013},
title ={Unusual Uses For Olive Oil},
journal = {Journal of Oleic Science},
volume = {34},
number = {1},
pages = {449--489},
url = {http://www.alexandermccallsmith.com/book/unusual-uses-for-olive-oil}}
```

---

##### Related material

+ [Presentation slides](presentation1.pdf)
+ [Summary of the paper](https://www.penguinrandomhouse.com/books/110403/unusual-uses-for-olive-oil-by-alexander-mccall-smith/) -->
