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
layers: "google_satellite,salmonriverwatershedstorymap" # basemap and overlaying layers
zoom: 9
lat: 50.484
lng: -119.983
---
### Case study

In this example, we show how Chinook salmon populations are changing in the Salmon River, British Columbia, Canada. In this region, Chinook salmon are important for the way of life for Indigenous communities, the economy, and the environment. Here, we show differences in trend significance depending on the start of a monitoring program. For example, if salmon monitoring only started 10 or 20 years ago (click on “since 2010” or “since 2000” buttons), then no significant downward trend would have been detected. However, if we begin our time-series analysis in 1984, then we see a significant downward trend: slope = -0.046 and p-value < 0.001.

{{< iframe width="100%" height="400" src="/embed/c2d_plotly.html" frameborder="0" style="border:0" >}}

*Data Source: Fisheries and Oceans Canada. 2021. NuSEDS-New Salmon Escapement Database System. Retrieved [here](https://open.canada.ca/data/en/dataset/c48669a3-045b-400d-b730-48aafe8c5ee6) on Jan 13, 2022.*

<!-- {{< figure src="images/ImageChallenge2d.png" 
class="mx-auto w-100 d-block" 
caption="Data Source: Fisheries and Oceans Canada. 2021. NuSEDS-New Salmon Escapement Database System. Retrieved [here](https://open.canada.ca/data/en/dataset/c48669a3-045b-400d-b730-48aafe8c5ee6) on Jan 13, 2022." 
>}} -->