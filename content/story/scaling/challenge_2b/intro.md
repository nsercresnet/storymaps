---
weight: 1 # the order to render
name: "intro" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "The choice of scale for summarizing data"
subitle: "Authors: Yiyi Zhang, Hugo Thierry, Peter Rodriguez"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 80 # translates to % of browser window
align: "center" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
splash: true # display the title and subtitle above the panel
layers: "google_satellite" # basemap and overlaying layers
zoom: 9
lat: 45.382
lng: -73.315
subtitle: "Authors: Yiyi Zhang, Hugo Thierry, Peter Rodriguez"
---
### Introduction

<!-- We often report data by summarizing individual information (e.g., at a pixel) to coarser scale analysis units (e.g., census division). In this example, we discuss the consequences of summarizing data to different units.

In addition to the resolution, boundaries used to aggregate smaller scale data may influence the visual assessment of ecosystem service supply and demand information and relationships. -->

We often report data by summarizing fine-scale information (e.g., at a pixel) to coarse-scale analysis or reporting units (e.g., census division). In this example, we discuss this challenge known as Modifiable Areal Unit Problem (MAUP) and how it may visually bias our understanding of ecosystem service supply and demand relationships. 