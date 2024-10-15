---
weight: 2 # the order to render
name: "case_study" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Case study: Human pressures at different scales"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 40 # translates to % of browser window
align: "left" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
# splash: true # display the title and subtitle above the panel
layers: "google_satellite,global_hf,national_hf,provincial_hf" # basemap and overlaying layers
layercontrol: true
zoom: 7
lat: 58.2
lng: -125.210678
---
### Case study
The human footprint is a cumulative index that quantifies the extent and the intensity of human pressures on ecosystems and biodiversity. We compared the Human footprint at three scales: global (Williams et al., 2020 <a href="../references/">[20]</a>), national (Hirsh-Pearson et al., 2022 <a href="../references/">[21]</a>), and provincial. 

The map on the right represents the state of human pressures in the northeast of British Columbia. From coarse (global) to detailed (provincial) scales, we can easily identify how roads are represented to different extents. The global model captures a broad perspective of human interventions, in which roads and settlements are the most visible features. This global map is improved with the national model, which integrates 12 layers of information, providing the appearance of more levels of detail such as oil and gas infrastructure and mining. The provincial map, which incorporates 16 layers of information, shows a more comprehensive state of the human footprint, including seismic lines, oil and gas wells, and infrastructure, and even recreational features.

{{< figure src="images/Legend_HF.png" 
class="mx-auto w-25 d-block"
caption="The Human Footprint Index represents cumulative pressure on the landscape, measured on a continuous scale from low to high." >}}


<!-- Leaflet map with ability to turn on and off the following three layers: Data/Originals_tiles/-->
<!-- Miguel's raster cell size comparison, large data file -->

