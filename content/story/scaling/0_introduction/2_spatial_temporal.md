---
weight: 2
name: "spatial_temporal"
layers: "esri_topo"
zoom: 9
lat: 45.4
lng: -75.6
background_media: "images/Front_image.jpg" 
visible: true
layout: "panel_float_card"
width: 40 # translates to % of browser window
align: "left" # align the entire panel
splash: false
title: "Spatial and temporal scales"
# subtitle: "NSERC ResNet HQP Scaling Group"
init_js: "Monteregie_map.init()"
---

### Spatial and temporal scales

When we move from the bottom to the top images below, we are increasing the size of the study area (i.e., spatial extent). When we move from the left to the right images below, we are increasing the number of pixels per area (i.e., spatial resolution), which allows for individual flowers to be distinguished.

{{< figure src="images/Intro_C1.png" class="d-block mx-auto w-75" caption="Moving across images increases spatial extent or resoltion. Image credit: Amanda Schwantes.">}}
<!--- Justify middle, no text on sides -->

In the image below, when we move from the bottom to the top images, we are expanding the time period for which we are collecting data. When we move from the left to the right images, we are increasing the detail (e.g., number of data points per year).

{{< figure src="images/Intro_C2.png" class="d-block mx-auto w-75" caption="Moving across images increases time period or temporal detail. Image credit: Amanda Schwantes.">}}
<!--- Justify middle, no text on sides -->
