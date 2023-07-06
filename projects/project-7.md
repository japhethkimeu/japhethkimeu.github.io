---
layout: project
type: project
image: images/change12-22.PNG
title: Temporal analysis of Lake Victoria basin wetlands 
permalink: projects/wetland_change_detection

# All dates must be YYYY-MM-DD format!
date: 2023-03-25
labels:
  - wetlands
  - landsat
  - google earth engine
  - arcgis pro
  - timeseries
summary: Detecting changes in wetlands using Landsat time-series satellite imagery
---

## Introduction
Lake Victoria wetlands have faced a myriad of threats arising from human activities such as pollution, overfishing, encroachment by people for agricultural activities and settlement. Wetlands provide food, water for human consumption and agriculture, provide a home to various animals and bird species that contribute to a rich biodiversity, and also play vital ecological functions such as flood mitigation and water purification. 
In Uganda, there has been efforts to protect and restore degraded wetlands through enforcement of wetland management policies and engaging relevant stakeholders. Information generated from satellite imagery analysis including wetland change maps is vital in making decisions and generating effective and sustainable wetland resource management policies as well as deliberating on ways of mitigating the loss of these vital ecosystems.

## Methodology
Time series remote sensing data from the Landsat series available since the early 1980s was used in this study. I analysed Landsat imagery of the study area for three periods spanning 20 years from 1999 to 2022. I sampled cloud-free images for each period and computed the median image in a specific period of 4 years. The images included Landsat 7 (1999 - 2002), Landsat 5 (2009 - 2012), and Landsat 8 (2019 - 2022). The three images were analysed as follows:
 * Extracting features to improve classification. The spectral features include NDVI, NDWI, and EVI.
 * Image classification
 * Change detection using the classified images
 * Computation of change areas

<img class="ui image" src="../images/wetland_classified.PNG">

## Results
Results show that over 14,000 hectares of wetlands were converted to urban and cropland between 2002 and 2022. The biggest wetland changes were observed between 2012 and 2022 as Kampala city expanded due to population pressure. Additionally, between 2012 and 2022, there was a substantial loss of cropland areas around the city.

 
<img class="ui image" src="../images/wetland_changes.PNG">

Source: <a href="https://github.com/japhethkimeu/wetlands-change-detection"><i class="large github icon"></i>Wetlands change detection</a>


