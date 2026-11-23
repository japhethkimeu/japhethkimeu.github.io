---
layout: project
type: project
image: images/change12-22.PNG
title: "Two-Decade Wetland Loss Analysis in the Lake Victoria Basin Using Landsat Time-Series"
permalink: projects/wetland_change_detection
date: 2023-03-25
labels:
  - wetlands
  - land cover change
  - Landsat
  - Google Earth Engine
  - ecosystem restoration
summary: "Over 14,000 hectares of Lake Victoria wetlands around Kampala lost to urban growth and farming in 20 years, with most of the loss after 2012. Evidence to target Uganda's wetland protection and restoration."
---

## What it shows
**Kampala's growth has swallowed more than 14,000 hectares of Lake Victoria wetlands in two decades.** Between 2002 and 2022, wetlands were converted to urban land and cropland. The loss accelerated sharply after 2012, as the city expanded under population pressure. In the same decade the city also absorbed much of the surrounding cropland.

These wetlands supply food and water, shelter rich bird and animal life, buffer floods and purify water. Uganda is trying to protect and restore them through policy enforcement and stakeholder engagement, but regulators can't act on loss they can't see. These maps show where wetlands have disappeared and how fast, so enforcement and restoration can be aimed at the places under most pressure. Because the method uses the free Landsat archive, it can be repeated to check whether protection is working.

<img class="ui image" src="../images/wetland_changes.PNG">

<img class="ui image" src="../images/wetland_classified.PNG">

## How it works
Cloud-free Landsat median composites for three periods (1999–2002, 2009–2012, 2019–2022), enriched with NDVI, NDWI and EVI and classified into land cover in Google Earth Engine. The three maps were then compared to measure the area of each type of change.

Source: <a href="https://github.com/japhethkimeu/wetlands-change-detection"><i class="large github icon"></i>Wetlands change detection</a>
