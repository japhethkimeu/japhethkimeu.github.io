---
layout: project
type: project
image: images/annual_soil_loss.JPG
title: "Soil Erosion Risk Assessment Using RUSLE in Google Earth Engine"
permalink: projects/soil_loss_assessment
date: 2022-12-04
labels:
  - soil erosion
  - RUSLE
  - land degradation
  - Google Earth Engine
  - Somalia
summary: "North-Western Somalia is losing an average of 36 tonnes of soil per hectare every year, concentrated on its steep highlands. The analysis shows land managers where conservation will save the most soil, and later became a public erosion app."
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/combined.PNG">
 </div>

## What it shows
**North-Western Somalia loses an average of 36 tonnes of soil per hectare every year.** The losses are far from evenly spread: they concentrate on the steep mountainous and hilly terrain, where rainfall washes topsoil off exposed slopes.

That gives land managers a clear starting point. Soil and water conservation works best on the slopes that are losing the most. The map shows where those slopes are, which supports land degradation neutrality targets and natural resource planning in a region where field data is scarce.

The analysis didn't stop at one region. I turned it into a public [Soil Erosion Risk Estimation app](https://ee-kimeu.projects.earthengine.app/view/soil-erosion-estimation) that anyone can run for their own area.

## How it works
The Revised Universal Soil Loss Equation (RUSLE; Renard et al. 1996), **A = R × K × LS × C × P**, implemented in Google Earth Engine. It combines rainfall erosivity, soil erodibility, slope length-steepness, cover management and support practice into annual soil loss in t/ha/yr. More about RUSLE: https://handle.nal.usda.gov/10113/11126.

Source: <a href="https://github.com/japhethkimeu/soil_loss_assessment"><i class="large github icon "></i>soil_loss_assessment</a>
