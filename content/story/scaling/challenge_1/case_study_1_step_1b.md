---
weight: 2.2 # the order to render
name: "case_study_1_1b" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Case Study 1: Organic carbon stocks of restored salt marshes along the upper Bay of Fundy"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 40 # translates to % of browser window
align: "left" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
# splash: true # display the title and subtitle above the panel
layers: "google_satellite,wprs_floodingzones,bof_sites" # basemap and overlaying layers
zoom: 17
lat: 45.823
lng: -64.402
suppress_nav: true
---

Each site was divided into three elevation zones that are flooded by tides differently throughout the year: the low zone is flooded by ~75% of high tides in a year, the mid zone is flooded by ~50% of high tides, and the high zone is flooded by ~25% of high tides. These zones were based on flooding frequency because decomposition of organic matter by microbes is slowed down in flooded, low-oxygen conditions. The layers displayed on the basemap for the Wood Point Rest Stop site were created by simulating different tidal flooding heights over a publicly available Digital Elevation Model (DEM) for New Brunswick <a href="../references/">[24]</a>

<!--{{< figure src="images/image7.png" 
class="mx-auto w-100 d-block" 
caption="The Wood Point Rest Stop (WPRS) study site (black rectangle). Figure by Brittney Roughan."
>}} -->

{{< gallery 
caption="The Aulac site flooded at high tide (12:24 PM) and almost fully exposed less than an hour and a half later (1:48 PM). Images by Brittney Roughan">}}
    {{< gallery-img src="images/Aulac_flood.jpg" >}}
    {{< gallery-img src="images/Aulac_noflood.jpg" >}}
{{< /gallery >}}
