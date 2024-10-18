---
weight: 2.6 # the order to render
name: "case_study_1_5" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Case Study 1: Organic carbon stocks of restored salt marshes along the upper Bay of Fundy"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 40 # translates to % of browser window
align: "left" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
# splash: true # display the title and subtitle above the panel
layers: "google_satellite,cumberlandbasin,cnwi_nb_ns,bof_sites" # basemap and overlaying layers
zoom: 11
lat: 45.8
lng: -64.5
---

#### Step 5:  Data processing and interpretation

<!--Once bulk density and % organic matter are determined, the ‘organic carbon density’ of each increment of the core can be estimated. Often % organic matter (%OM) is converted to % organic carbon (%OC) in salt marshes using a known conversion equation published in the scientific literature or roughly estimated by simply dividing %OM by 2. Some studies choose to determine the exact amount of organic carbon (%OC) in their samples by conducting ‘elemental analysis’ or sending the samples to another lab to do this analysis. More and more studies are now sending at least a subset of samples away to determine their own %OM-to-%OC conversion equations. Either way, this step involves more time to process samples or more money to pay for the analysis. In addition, soil samples should be treated to remove any inorganic carbon so elemental analysis results only reflect total organic carbon. The figure below is pulled directly from Craft et al. 1991 <a href="../references/">[1]</a> and shows the relationship between %OM and %OC for brackish and salt marsh sediments in North Carolina. For the data presented below in this case study, a local equation for %OM-to%OC was developed using data from sites located in the Upper Bay of Fundy. -->

Once bulk density and % organic matter are determined, the ‘organic carbon density’ of each increment of the core can be estimated. Often % organic matter (%OM) is converted to % organic carbon (%OC) in salt marshes using a known conversion equation published in the scientific literature. Some studies choose to determine the exact amount of organic carbon (%OC) in their samples by conducting ‘elemental analysis’ and creating their own %OM-to-%OC conversion equation for their specific region. This step involves more time to process samples or more money to pay for the analysis. In addition, soil samples should be acidified to remove any inorganic carbon present so elemental analysis results only reflect total organic carbon. Maxwell et al. (2023) <a href="../references/">[3]</a> has recently published the most comprehensive <a href="https://www.nature.com/articles/s41597-023-02633-x/figures/4" target="_blank">conversion equation</a> for soil organic matter (SOM) to soil organic carbon (SOC) in tidal marshes to date. 


<!--{{< figure src="images/Craft1991.jpg" 
class="mx-auto w-75 d-block" 
caption="Figure from Craft et al. 1991." >}}-->

{{< figure src="images/carbonstock.jpg" 
class="mx-auto w-100 d-block" 
caption="Figure by Brittney Roughan." 
>}}

<!--Once %OC of the increment is determined, this can be multiplied by the bulk density (g/cm<sup>3</sup>) to determine the organic carbon density of the core. Organic carbon density (g OC/cm<sup>3</sup>) is then multiplied by the height of each increment (5 cm in this example) to determine the amount of carbon within each core depth increment (g OC/cm<sup>2</sup>). Then all increments are added together to get the total ‘soil organic carbon stock’ throughout the core’s depth. This organic carbon stock (g OC/cm<sup>2</sup> to 50 cm depth) can be scaled up to larger areas and compared to other studies. A common unit for carbon stock is megagrams (or tonnes) per hectare (Mg/ha). The figure below shows how to get from bulk density and %OC to total organic carbon stock and how to convert g/cm<sup>2</sup> to Mg/ha using an example core from this case study.-->

Once %OC of the increment is determined, this can be multiplied by the bulk density (g/cm<sup>3</sup>) to determine the organic carbon density of the core. Organic carbon density (g OC/cm<sup>3</sup>) is then multiplied by the height of each increment (5 cm in this example) to determine the amount of carbon within each core depth increment (g OC/cm<sup>2</sup>). Then all increments are added together to get the total ‘soil organic carbon stock’ throughout the core’s depth. This organic carbon stock (g OC/cm<sup>2</sup> to 50 cm depth) can be scaled up to larger areas and compared to other studies. A common unit for carbon stock is megagrams (or tonnes) per hectare (Mg/ha). The figure above shows how to get from bulk density and %OC to total organic carbon stock and how to convert g/cm<sup>2</sup> to Mg/ha using an example core from this case study.






