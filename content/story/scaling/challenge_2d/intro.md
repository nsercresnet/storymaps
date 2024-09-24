---
weight: 1 # the order to render
name: "intro" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Time period matters"
subtitle: "Author: Amanda Schwantes"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 80 # translates to % of browser window
align: "center" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
splash: true # display the title and subtitle above the panel
layers: "google_satellite" # basemap and overlaying layers
zoom: 9
lat: 50.484
lng: -119.983
---
### Introduction

To understand whether an ecosystem is changing, we measure it over time. However, if we only measure the ecosystem over a short time, then we may not detect a change, even when the ecosystem has changed. This example explores how the monitoring time-period influences outcomes.

Often we use time series analysis to understand whether an ecosystem property or service is changing over time. The temporal extent (e.g., time frame or period) of the monitoring data can affect outcomes. For shorter time-series or time-series with high variability, we may not have a correct historical baseline to detect change. For example, if monitoring data does not extend far enough into the past, then an insignificant trend could be interpreted as evidence for stability or no effect, when in reality the system might already be in a degraded state.

<!--- Leaflet map with shapefile of study region. Content/archive_agm2023/Challenges/Challenge 2d/Archive.zip -->