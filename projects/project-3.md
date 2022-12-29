---
layout: project
type: project
image: images/annual_soil_loss.JPG
title: Implementation of RUSLE method in Google Earth Engine to estimate soil loss
permalink: projects/soil_loss_assessment
# All dates must be YYYY-MM-DD format!
date: 2022-12-04
labels:
  - Google Earth Engine
  - JavaScript
  - soil loss
  - land degradation
summary: Estimating soil loss using RUSLE in Google Earth Engine.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/combined.PNG">
 </div>


Revised Universal Soil Loss Equation (RUSLE) developed by Renard et al. (1996) is one of the methods used in estimating soil loss. In this project, I implemented RUSLE in GEE to estimate annual soil loss in North-Western Somalia. RUSLE is described by A = R * K * LS * C * P, where, A is the mean annual soil loss in metric tonnes/ha/year, R is rainfall erosivity factor, K is soil erodibility factor, LS is slope length-steepness factor, C is cover and management factor and P is erosion management factor. The mean annual soil loss in the study area is 36.05 t/ha/yr. Steep sloping areas especially the mountanious/hilly (see soil loss map) areas have the highest soil loss rates in the region. More about RUSLE https://handle.nal.usda.gov/10113/11126.

Source: <a href="https://github.com/japhethkimeu/soil_loss_assessment"><i class="large github icon "></i>soil_loss_assessment</a>

