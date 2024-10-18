---
weight: 2 # the order to render
name: "case_study" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Case Study"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 40 # translates to % of browser window
align: "left" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
# splash: true # display the title and subtitle above the panel
layers: "google_satellite,ndvi_break_1km,ndvi_break_500m,ndvi_break_250m,algonquin_pilot_study_area_v1,forest_fire_year_2003_2020_v1,forest_harvest_year_2003_2020_v1" # basemap and overlaying layers
zoom: 11.5
lat: 46.140
lng: -78.30
layercontrol: true
---
### Case study

In the figure below, we show two major forest disturbance agents (panel a) and the results of a geospatial trend analysis (panel b to d) over a relatively small study area (26,000 ha) located along the northern boundary of Algonquin Provincial Park (Ontario). The greenness of forests, as measured by the Normalized Difference Vegetation Index (NDVI), shows trend breakpoints over an 18-year long period (2003-2020). Trend breakpoints refer to structural (abrupt) changes in the trend line of a measurement. Trend breakpoints can be positive or negative and can result from natural or anthropogenic disturbances.

When using satellite derived (MODIS sensor) NDVI at a 250 m (16-day) resolution (panel b) we find 312 different trend breakpoints in the data. Most of these are negative breakpoints (orange color pixels), meaning that some forest areas have experienced important abrupt decreases in greenness at some point in time. However, there are also some forest areas that have seen significant abrupt increases (turquoise color pixels) in greenness at a point in time. When a 500 m (16-day) resolution NDVI is used instead (panel c), the number of breakpoints drops to 71. Similarly, when a 1 km (16-day) resolution NDVI is used (panel d), the number of breakpoints further decreases to 17.

Interestingly, not only does the number (and direction/sign) of forest pixels with trend breakpoints change depending on the resolution of the data but also the location of these pixels over the study area. Some of these trend breakpoint pixels spatially and temporally overlap with forest harvest and fire events. The largest overlaps occur when using the finest spatial resolution (250 m) data. Thus, the spatial resolution of a dataset may influence the results obtained and in turn, the management decisions that may arise from them.

{{< figure src="images/ndvi_breakpts_direction_v4.png" 
class="mx-auto w-100 d-block" 
caption="Forest disturbance (a) and NDVI trend breaks (b, c and d) in pilot study area within Algonquin Provincial Park. Created by Peter Rodriguez." >}}


{{< figure src="images/legend1.png" 
class="mx-auto w-50 d-block" 
caption="NDVI trend break types at three different resolutions (not to scale). This is a legend for the map on the right.">}}


<!--- Use shapefiles in resnet_upscaling_story_map folder over esri earth imagery for challenge background --->
