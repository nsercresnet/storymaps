---
weight: 3 # the order to render
name: "best_practices" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Best practices and opportunities"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 80 # translates to % of browser window
align: "center" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
# splash: true # display the title and subtitle above the panel
layers: "google_satellite" # basemap and overlaying layers
zoom: 11
lat: 46.140
lng: -78.305
---
### Best practices and opportunities

In cases where different data resolutions are available, the recommendation is to use data at the finest spatial resolution to ensure that potentially relevant ecological patterns are not missed. Even though fine scale data usually leads to improved accuracy (figure below, panels a & b), there are several constraints to keep in mind such as data availability, data storage, computing power, time, and financial resources (figure below, panel c). Finer grain size (i.e., smaller pixel size) usually leads to improved accuracy but some processes actually plateau at a certain resolution and there is no need to go finer (figure below, panel b). This threshold is often used as a baseline for future studies. Higher resolution often comes with increases in cost and time and hence, it is important to identify the most optimal resolution (grain size) for a given study based on resources available.

{{< figure src="images/resnet_upscaling_grain_size2.png" 
class="mx-auto w-75 d-block" 
caption="Created by Peter Rodriguez & Amanda Schwantes" 
>}}
