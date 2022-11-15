---
layout: project
type: project
image: images/quantumBlack.jpeg
title: Gully feature identification using Random Forest
permalink: projects/vacay
# All dates must be YYYY-MM-DD format!
date: 2022-11-15
labels:
  - Jupyter Notebook
  - Python
  - Machine Learning
summary: Random Forest classification of Sentinel 2 images to identify gullies
---

<img class="ui medium right floated rounded image" src="../images/quantumBlack.jpeg">

The United Nations Convention to Combat Desertification (UNCCD) estimates that two thirds of productive land in Africa is degraded (UNCCD 2013). Soil degradation is one of the major forms of land degradation and occurs through water erosion, wind erosion, chemical and physical deterioration. According to Jones et al. (2013), water erosion accounts for forty six percent of land degradation in sub-Saharan Africa. In most tropical regions of Africa, water erosion is accelerated by deforestation, population increase, and flooding due to heavy rainfall incidents. Water erosion manifests in various forms; sheet, rill and gully erosions. Sheet erosion occurs through surface run-off washing away considerable amount of nutrients from top soil thereby rendering it unproductive. In cases where massive water quantities flow down susceptible sloping and gentle terrain, rill and gully erosion occurs.
Gully erosion is the most destructive form of soil erosion since it can remove and transport huge quantities of soil (Daba, Rieger, and Strauss 2003).
Machine-learning algorithms have become common in remote sensing tasks such as image classification. I used Random Forest to classify Sentinel 2 images into two classes (i.e. binary classification). Random forest is an ensemble learning algorithm based on the idea that a combination of bootstrap aggregated classifiers perform better than a single classifier (Breiman 2001). The bootstrap component means that each individual tree is parameterized using a randomly sampled set of observations with replacement from the training data (Hastie, Tibshirani, and Friedman 2009). This helps to de-correlate the trees thereby reducing multi-collinearity. The proportion of observations that are not used for this purpose are included in the evaluation and are referred to “out-of-bag” samples. Several of these decision tree models are created on different groupings of the input variables and the resultant output is the unweighted majority vote of each class that is averaged across all trees (Breiman 2001).
in this project, I am going to identify gully erosion/features using machine-learning and sentinel 2 imagery. The data required includes satellite imagery and reference samples. I used Sentinel 2 images downloaded from https://scihub.copernicus.eu/dhus/#/home. The images were downloaded as S2 Level 1C TOA and are not corrected of atmospheric effects. I used SNAP Sen2Cor to correct atmospheric effects and get S2 Level 2A BOA. Training and validation samples were digitized in a GIS environment.

Source: <a href="https://github.com/neli12/data-science/tree/main/MckDatathon"><i class="large github icon"></i>data-science/MckDatathon</a>

