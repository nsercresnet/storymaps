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
layers: "google_satellite,mendes_study_area,carbon_vacant_lots" # basemap and overlaying layers
zoom: 10
lat: 46.842
lng: -71.565
---
### Case study

In this case study, we explore the relationship between soil carbon and plant cover in vacant lots in Quebec City. The vacant lots were carefully chosen to cover the full range of plant cover. However, if a scientist only picked a few of these lots (like the green dots on the two left-hand figures), they might mistakenly think the relationship between soil carbon and plant cover is linear (as shown by the green line). This would lead to incorrect predictions for the entire area. But when we look at data from the whole study region (shown on the right), we see the relationship is actually non-linear (the gray line). In areas with high plant cover, other factors, like soil type or land use history, may play a role in explaining the carbon levels.


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