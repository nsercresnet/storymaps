---
weight: 2 # the order to render
name: "case_study" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Case study"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 40 # translates to % of browser window
align: "left" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
# splash: true # display the title and subtitle above the panel
layers: "google_satellite,bombus_pcrop_watershed_monteregie,bombus_pcrop_3km_monteregie" # basemap and overlaying layers
# layers: "google_satellite,bombus_pcrop_watershed_monteregie,bombus_pcrop_3km_monteregie" # basemap and overlaying layers
zoom: 9
lat: 45.382
lng: -73.315
---
### Case study

Pollination supply and demand aggregated to watersheds (left) tend to show ecosystem service surplus (i.e. higher ratios) at areas with little demand, while the supply and demand relationships represented at 3km grid cells (right) can help identify more precisely high demand areas that could benefit from more agricultural support.

{{< figure src="images/supply-demand_ratio_rescale.png" 
class="mx-auto w-100 d-block" 
caption="Supply-demand ratio. Left: Ratio of pollination supply potential to the area of dependent crops summarized to the watersheds. Right: Ratio of pollination supply potential to the area of dependent crops summarized to a 3km grid. Created by Yiyi Zhang." 
>}}