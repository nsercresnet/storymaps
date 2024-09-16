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
layers: "google_satellite,mendes_study_area" # basemap and overlaying layers
zoom: 10
lat: 46.842
lng: -71.565
---
### Case study

In this case study, we show the relationship between soil carbon and plant cover in vacant lots in Quebec city. In this study, vacant lots were carefully selected to represent the entire range of plant cover. However, we could have selected only a subset of these vacant lots, for example only the green dots in the two figures on the left. The relationship between soil carbon and plant cover only within this subset (green dots in the two figures on the left) is linear (green line in the figure on the right) and would lead to an incorrect extrapolation to the whole study region. When using data from the whole study region (e.g., increasing the spatial extent), we find that the relationship is actually non-linear (gray line). In vacant lots with high plant cover, other factors (e.g., soil type, land use history, etc.) might be needed to better explain the variability of carbon.


<!-- {{< gallery 
caption="Data source: Mendes P; Bourgeois B; Pellerin S; Ziter CD; Cimon-Morin J; Poulin M. Linkages between plant functional diversity and soil-based ecosystem services in urban and peri-urban vacant lots. Urban Ecosystems. 10.1007/s11252-023-01470-5" >}}
    {{< gallery-img src="images/fig2cLeft.png" >}}
    {{< gallery-img src="images/fig2cMiddle.png" >}}
    {{< gallery-img src="images/fig2cRight.png" >}}
{{< /gallery >}} -->

<div class="d-flex">
{{< figure src="images/fig2cLeft.png" 
class="mx-auto w-25" 
caption="Locations of sampled vacant lots." 
>}}{{< figure src="images/fig2cMiddle.png" 
class="mx-auto w-25" 
caption="Linear relationship observed when only a subset of the vacant lots is considered (green dots)." 
>}}{{< figure src="images/fig2cRight.png" 
class="mx-auto w-25" 
caption="Non-linear relationship when all vacant lots are considered. Plant cover (%) can be greater than 100% when there is more than one layer of vegetation (for example trees and herbs)." 
>}}
</div>

<figcaption class="figure-caption text-center">Data source: Mendes P; Bourgeois B; Pellerin S; Ziter CD; Cimon-Morin J; Poulin M. Linkages between plant functional diversity and soil-based ecosystem services in urban and peri-urban vacant lots. Urban Ecosystems. 10.1007/s11252-023-01470-5</figcaption>