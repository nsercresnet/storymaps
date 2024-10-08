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
layercontrol: true
# layers: "google_satellite,bombus_pcrop_watershed_monteregie,bombus_pcrop_3km_monteregie" # basemap and overlaying layers
zoom: 9
lat: 45.382
lng: -74.25
---
### Case study

<!--Pollination supply and demand aggregated to watersheds (left) tend to show ecosystem service surplus (i.e. higher ratios) at areas with little demand, while the supply and demand relationships represented at 3km grid cells (right) can help identify more precisely high demand areas that could benefit from more agricultural support. -->

Pollination is beneficial to the production of certain crops such as soybean and fruit trees. Landscape areas with more nesting and floral resources are pollinator-suitable habitats. Pollinators such as bumble bees can fly from their habitats to nearby (~3km) crop fields and provide pollination service. We summarize pollinator abundance index estimated using InVEST model, and pollination demand estimated based on the area of pollinator-dependent crops into 3km cells that can better capture effective pollination. We also summarize the information into the watersheds, which is a common scale for governance activities, to compare supply-demand relationship. 

In the figure below, areas with no demand are observed in panel a, but not in panel b. In panel a, most cells show high demand-low supply relationship, while in panel b, most watersheds show more balanced high demand-high supply relationship. Cells with low demand and high supply tend to be in watersheds with the same relationship. When making decisions among the watersheds, areas that could benefit from improved effective pollination supply (e.g., cells with high demand and low supply) may not be evident at the watershed-level results.

{{< figure src="images/choice_of_scale.jpg" 
class="mx-auto w-100 d-block" 
caption="Supply and demand of pollinator abundance index summarized to 3km cells (a) and watersheds (b). Note: values are classified based on the median of supply and demand. High: values above median, low: values below median. Created by Yiyi Zhang." >}}



<!-- Supply-demand ratio. Left: Ratio of pollination supply potential to the area of dependent crops summarized to the watersheds. Right: Ratio of pollination supply potential to the area of dependent crops summarized to a 3km grid. Created by Yiyi Zhang. -->