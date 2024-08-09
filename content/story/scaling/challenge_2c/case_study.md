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
layers: "google_satellite" # basemap and overlaying layers
zoom: 9
lat: 46.842
lng: -71.365
---
### Case study

In this case study, we show the relationship between soil carbon and plant cover in vacant lots in Quebec city. Plant cover can be greater than one in densely vegetated vacant lots when leaves overlap. In this study, vacant lots were carefully selected to represent the entire range of plant cover. However, a less careful scientist could have selected only a subset of these vacant lots (green dots on map). The relationship between soil carbon and plant cover only within this subset (green dots on map) is linear (green line) and would lead to an incorrect extrapolation to the whole study region. When using data from the whole study region (e.g., increasing the spatial extent), we find that the relationship is actually non-linear (gray line). In vacant lots with high plant cover, other factors (e.g., soil type, land use history, etc.) might be needed to better explain the variability of carbon.


{{< gallery 
caption="Data source: Mendes P; Bourgeois B; Pellerin S; Ziter CD; Cimon-Morin J; Poulin M. Linkages between plant functional diversity and soil-based ecosystem services in urban and peri-urban vacant lots. Urban Ecosystems. 10.1007/s11252-023-01470-5" >}}
    {{< gallery-img src="images/fig2cLeft.png" >}}
    {{< gallery-img src="images/fig2cMiddle.png" >}}
    {{< gallery-img src="images/fig2cRight.png" >}}
{{< /gallery >}}
