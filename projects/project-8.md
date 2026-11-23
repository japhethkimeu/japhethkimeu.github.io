---
layout: project
type: project
image: crop_images/classification1.PNG
title: "Crop Area Estimation and Yield Prediction Using Remote Sensing and Regression Modelling"
permalink: projects/Crop-production
date: 2023-05-05
labels:
  - crop mapping
  - food security
  - NDVI
  - Sentinel-2
  - climate-smart agriculture
summary: "Crop area estimated within 18% of official statistics, and 75% of yield variation explained, from satellite imagery alone in Córdoba, Argentina. A faster, cheaper complement to farm-by-farm crop surveys."
---
## What it shows
**Satellites can estimate how much was planted and how well it will yield, close enough to official statistics to be useful.** In Córdoba, Argentina, planted area for soybean, maize, millet and peanut came within 18% of Ministry of Agriculture figures for the 2019/20 season. A single satellite measure of crop vigour explained 75% of the variation in yield between regions.

Governments plan food security, trade and input support around crop statistics. Those statistics still depend on field officers travelling farm to farm and extrapolating from samples, which is slow, costly and often too coarse to rely on. A satellite estimate covers every field and can be produced during the season, giving planners an earlier and fuller picture. Adding soil, rainfall and temperature data would tighten the estimates further.

<img class="ui image" src="../crop_images/combined1.PNG">

<img class="ui image" src="../crop_images/combined.PNG">

## How it works
Sentinel-2 imagery from the January–March 2020 peak-greenness window, when crop NDVI is highest, classified to measure planted area. Mean NDVI per region was regressed against [Ministry of Agriculture, Livestock and Fisheries](https://datos.magyp.gob.ar/dataset) yield data (R² = 0.78, adjusted R² = 0.75), and the model was used to predict the following season's yield.

Code: <a href="https://github.com/japhethkimeu/crop-production"><i class="large github icon"></i>Crop production</a>
