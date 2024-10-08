---
weight: 1 # the order to render
name: "intro" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Spatial resolution matters"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 80 # translates to % of browser window
align: "center" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
splash: true # display the title and subtitle above the panel
layers: "google_satellite" # basemap and overlaying layers
zoom: 11
lat: 46.140
lng: -78.305
subtitle: "Authors: Peter Rodriguez, Hugo Thierry, Yiyi Zhang, Amanda Schwantes"
---
### Introduction

We often need detailed data to detect change. In this example, we discuss why we need data at finer pixel sizes to detect forest losses and gains.

When we change the spatial resolution of a pixel, we change the number and type of elements (for example land cover types) that compose it. This can impact the results of our studies, especially those where we attempt to classify pixels based on their composition.

{{< figure src="images/ConceptualFigureMixedPixel.png" 
class="mx-auto w-50 d-block" 
caption="Created by Amanda Schwantes and Peter Rodriguez" 
>}}