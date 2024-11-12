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
The human footprint is a cumulative index that quantifies the extent and the intensity of human pressures on ecosystems and biodiversity. We compared the Human footprint at three scales: global (Williams et al., 2020 <a href="../references/">[20]</a>), national (Hirsh-Pearson et al., 2022 <a href="../references/">[21]</a>), and provincial <a href="../references/">[22]</a>. 

<!--The map on the right represents the state of human pressures in the northeast of British Columbia. From coarse (global) to detailed (provincial) scales, we can easily identify how roads are represented to different extents. The global model captures a broad perspective of human disturbances, in which roads and settlements are the most visible features. This global map is improved with the national model, which integrates 12 layers of information, providing the appearance of more levels of detail such as oil and gas infrastructure and mining. The provincial map, which incorporates 16 layers of information, shows a more comprehensive state of the human footprint, including seismic lines, oil and gas wells, and infrastructure, and even recreational features.
-->
The interactive maps on the right represent the state of human pressures in the northeast of British Columbia. From coarse (Global Human Footprint) to detailed (Provincial Human Footprint) spatial resolution (scales), we can easily identify how roads are represented at different extents. The global model captures a broad perspective of human disturbances in which roads and settlements are the most visible features. The resolution of this global map is improved with the national model (National Human Footprint), which integrates 12 layers of information, providing more levels of detail such as oil and gas infrastructure and mining. The provincial map (Provincial Human Footprint), which incorporates 16 layers of information, shows a more comprehensive state of the human footprint, including seismic lines, oil and gas wells, human infrastructure, and even recreational features. By *turning on and off the different spatial layers* on the right, differences in spatial resolution can be seen.

The static maps below show the same human footprint models but zoomed in and centered on Fort Nielson, British Columbia. These maps show the same spatial extent for a global (a) <a href="../references/">[20]</a>, a national (b) <a href="../references/">[21]</a> and a provincial footprint model (c) <a href="../references/">[22]</a>. A gradient of increased spatial resolution is shown from a coarser global model (a) with less detail to a finer provincial model (c) with more details. The map in (a) shows less detail but the original source map covers the entire globe. The map in (b) shows more details than (a) but the original source map only covers Canada. The map in (c) reveals more details than (b) but the original source map only covers the province of British Columbia. A similar spatial resolution gradient can be replicated in the spatial layers on the right by *zooming in and turning on and off the different spatial layers*. 


{{< figure src="images/three_panels_fig1_letters1.png" 
class="mx-auto w-100 d-block"
caption="The outputs (maps) of three different human footprint models for a sample area centered on Fort Nielson, British Columbia. These cropped maps show the same spatial extent for a global (a), a national (b) and a provincial footprint model (c). A gradient of increased spatial resolution is shown from a coarser global model with less detail (a) to a finer provincial model with more details (c). A similar spatial resolution gradient can be replicated in the spatial layers on the right by zooming in and turning on and off the three different layers. The legend for both the static maps above and the interactive layers on the right is shown below." >}}


{{< figure src="images/Legend_HF.png" 
class="mx-auto w-25 d-block"
caption="The Human Footprint Index represents cumulative pressure on the landscape, measured on a continuous scale from low to high." >}}


<!-- Leaflet map with ability to turn on and off the following three layers: Data/Originals_tiles/-->
<!-- Miguel's raster cell size comparison, large data file -->

