---
weight: 2 # the order to render
name: "case_study_1" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Case Study 1: Organic carbon stocks of restored salt marshes along the upper Bay of Fundy"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 40 # translates to % of browser window
align: "left" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
splash: true # display the title and subtitle above the panel
layers: "google_satellite,bof_sites" # basemap and overlaying layers
zoom: 11
lat: 45.8
lng: -64.8
---

<!-- ### Case Study 1: Organic carbon stocks of restored salt marshes along the upper Bay of Fundy -->

#### Step 1:  Choosing representative sites and study areas

<!--Four study sites in the Upper Bay of Fundy along the Cumberland Basin were chosen to represent salt marshes at different stages of restoration:  Converse - newly restored, Aulac - restored over 10 years ago, John Lusby - passively restored over 50 years ago, and Wood Point Rest Stop - natural reference site. Sites were chosen to be close to one another (<10 km apart) so environmental conditions like tides and weather were similar between sites. -->

Four sites were chosen in this study to represent salt marshes at different stages of restoration: Converse - newly restored, Aulac - restored over 10 years ago, John Lusby - passively restored over 70 years ago, and Wood Point Rest Stop - natural reference site. Sites were located close to one another (<10 km apart) so environmental conditions like tides and weather were similar between sites. The basemap shows the extent of tidal marsh in the Upper Bay of Fundy along the Cumberland Basin based on geospatial data available in the Canadian National Wetlands Inventory <a href="../references/">[1]</a>.

<!--{{< figure src="images/image4.png" 
class="mx-auto w-100 d-block" 
caption="Map showing four study sites. Map by Brittney Roughan."
>}} -->

{{< gallery 
caption="Photos of the four study sites: Converse, Aulac, John Lusby, and Wood Point Rest Stop. Images by Brittney Roughan.">}}
    {{< gallery-img src="images/Converse.JPG" >}}
    {{< gallery-img src="images/Aulac.JPG" >}}
    {{< gallery-img src="images/JohnLusby.JPG" >}}
    {{< gallery-img src="images/WPRS.JPG" >}}
{{< /gallery >}}



<!--The Wood Point Rest Stop (WPRS) will be used as an example in this case study. Each site was divided into three elevation zones that are flooded by tides differently throughout the year: the low zone is flooded by 75% of high tides in a year, the mid zone flooded by 50% of high tides, and the high zone is flooded by 25% of high tides. These zones are based on flooding frequency because decomposition of organic matter by microbes is slowed down in flooded, low-oxygen conditions. -->

Each site was divided into three elevation zones that are flooded by tides differently throughout the year: the low zone is flooded by ~75% of high tides in a year, the mid zone is flooded by ~50% of high tides, and the high zone is flooded by ~25% of high tides. These zones were based on flooding frequency because decomposition of organic matter by microbes is slowed down in flooded, low-oxygen conditions. The photos below show just how much water moves in and out of the study sites in a short amount of time during a spring high tide.

<!--{{< figure src="images/image7.png" 
class="mx-auto w-100 d-block" 
caption="The Wood Point Rest Stop (WPRS) study site (black rectangle). Figure by Brittney Roughan."
>}} -->

{{< gallery 
caption="The Aulac site flooded at high tide (12:24 PM) and almost fully exposed less than an hour and a half later (1:48 PM). Images by Brittney Roughan">}}
    {{< gallery-img src="images/Aulac_flood.jpg" >}}
    {{< gallery-img src="images/Aulac_noflood.jpg" >}}
{{< /gallery >}}

#### Step 2:  Collection of sediment cores

<!-- <div class="images-container"> 
![fig3](images/survey.jpg " ") 
{width="50%"}

![fig4](images/image40.png " ")
{width="40%"}

![fig5](images/image17.png " ") 
{width="40%"} 
</div> -->

<!--Three random points within each zone were chosen for core extraction using Geographic Information System (GIS) software (ArcGIS Pro) and the location of each point was surveyed using a high-accuracy GPS system. In total, nine cores were collected from each study site. The photo below (left) shows someone surveying core locations at the Aulac site. The maps below show the location of nine cores in the Wood Point Rest Stop study site within the three elevation zones. -->

Within a designated study area of each site, three random points within each zone were chosen for core extraction using Geographic Information System (GIS) software (ArcGIS Pro) and the location of each point was surveyed using a high-accuracy GPS system. In total, nine cores were collected from each study site. The basemap shows where the nine cores were collected in the Wood Point Rest Stop study site within the three elevation zones.

{{< gallery 
caption="Surveying core locations at the Aulac site. Image by Brittney Roughan">}}
    {{< gallery-img src="images/survey.jpg" >}}
{{< /gallery >}}

Cores were collected using a gouge auger (images below), one of the many types of ‘corers’ available to use by soil carbon scientists. Other coring types include the ‘Russian peat corer’ (extracts half a core) and manual extraction (hammering a sharpened tube into the ground). Each of these methods will create different levels of core ‘compaction’, which can affect the overall length of the core and influence the estimate of how much soil organic carbon is contained within each core. Depending on the length of the core, the process of pushing the coring device into the ground and extracting a core can be physically demanding and often requires teamwork.

{{< gallery 
caption="A gouge auger, a type of ‘corer’ used by soil carbon scientists. Images by Brittney Roughan." >}}
    {{< gallery-img src="images/corer1.jpg" >}}
    {{< gallery-img src="images/corer2.jpg" >}}
{{< /gallery >}}


Transport and handling of cores after they are taken out of the ground is another important consideration for field work. Sometimes cores are cut apart and sub-sampled in the field, and other times cores are packed in rigid plastic shells, wrapped in plastic-wrap, and refrigerated or frozen before being processed back in the lab. In salt marshes, researchers often have to walk far into study sites across uneven terrain with heavy equipment (like the corer and a cooler) to retrieve cores and bring them back. 

{{< gallery 
caption="Transferring a core to PVC pipe and walking to the John Lusby site. Photos by Brittney Roughan." >}}
    {{< gallery-img src="images/corePVC.jpg" >}}
    {{< gallery-img src="images/cooler.jpg" >}}
{{< /gallery >}}

#### Step 3:  Processing of cores in the lab

Once back in the lab, processing the core starts. The cores are photographed and different features like soil colour and texture are described and recorded. Then cores are divided into different increments depending on the goals of the study. For this study, 5 cm increments were chosen for a total of 10 per 50 cm core, which means that 360 individual samples were processed! When dividing cores, a compression factor should be used to adjust the increment length based on the compaction measured in the field. Compaction is often assumed equal across the entirety of the core, unless compaction is measured periodically throughout the core extraction process in the field.

{{< gallery 
caption="Processing of cores in the lab. Images by Brittney Roughan." >}}
    {{< gallery-img src="images/con_h3.jpg" >}}
    {{< gallery-img src="images/cutcore.jpg" >}}
{{< /gallery >}}

<!--To calculate how much organic carbon is in a core, two measurements are needed - ‘bulk density’ and ‘organic carbon content’ or ‘% organic carbon’. Core increments are usually sampled for bulk density first, which is a measure of the dry weight of soil within a known volume of the core. In the photo below, a metal cylinder was inserted into the centre of each 5 cm increment. The soil sample was extracted using a syringe plunger and then dried in an oven (see Step 4). Often the same soil sample is also used to determine the organic carbon content of the increment, but others can be cut from the core and stored until they are processed.-->

To calculate how much organic carbon is in a core, two measurements are needed - ‘bulk density’ and ‘organic carbon content’ or ‘% organic carbon’. Core increments are usually sampled for bulk density first, which is a measure of the dry weight of soil within a known volume of the core. In the photos below, a metal cylinder was inserted into the centre of each 5 cm increment. The soil sample was extracted using a syringe plunger and then dried in an oven (see Step 4). The same soil sample can be used to determine the organic carbon content of the increment, but others can be cut from the core and stored until they are processed.

{{< gallery 
caption="Measuring bulk density. Images by Brittney Roughan" >}}
    {{< gallery-img src="images/bd3.jpg" >}}
    {{< gallery-img src="images/bd4.jpg" >}}
{{< /gallery >}}

<!-- ![fig13 top-left](images/bd1.jpg) 
![fig14 top-right](images/bd2.jpg) 
![fig15 bottom-left](images/bd3.jpg) 
![fig16 bottom-right](images/bd4.jpg)  -->

Once processing is done, any remaining core segments are often archived and frozen for future analyses. Freezer and refrigerator space is a very important factor to consider when taking soil cores and designing the field study, as cores should be kept cold (< 4℃) to prevent decomposition of organic matter by microbes. 

{{< gallery 
caption="Archived core half being prepped for freezing. Image by Brittney Roughan." >}}
    {{< gallery-img src="images/wp_l1.jpg" >}}
{{< /gallery >}}

#### Step 4:  Lab analyses for bulk density and loss-on-ignition (LOI)

<!--The soil samples of known volume taken from the core are first dried to determine the bulk density. Wet samples are placed in individually labeled tins, weighed, and then dried at 60 ℃ in a drying oven for 24-72 hours (or until a consistent dried weight is reached). After they are completely dry, they are re-weighed to determine dry weight of the soil sample. The photos below show the dried soil cylinders in a dessicator after the oven, which ensures the samples are fully dried before being re-weighed. Bulk density is written as the dry weight of soil divided by the known volume of the sample (grams per cm<sup>3</sup>). Low bulk density means there is not a lot of soil within the volume of core sampled, which means the soil is less densely packed and there are more air pockets. Soils with low bulk density often have high organic matter content and water-holding capacity (like a sponge!). -->

Wet samples are placed in individually labeled tins, weighed, and then dried at 60 ℃ in a drying oven for 24-72 hours (or until a consistent dried weight is reached). After they are completely dry, they are re-weighed to determine dry weight of the soil sample. The images below show the dried soil cylinders in a desiccator, which allows the samples to cool down to room temperature without absorbing any moisture before being re-weighed. Bulk density is written as the dry weight of soil divided by the known volume of the sample (grams per cm<sup>3</sup>). Low bulk density means there is not a lot of soil within the volume of core sampled, which means the soil is less densely packed and there are more air pockets. Soils with low bulk density often have high organic matter content and water-holding capacity (like a sponge!).

{{< gallery 
caption="Dried bulk density samples in the desiccator before re-weighing. Images by Brittney Roughan." >}}
    {{< gallery-img src="images/dry1.jpg" >}}
    {{< gallery-img src="images/dry2.jpg" >}}
{{< /gallery >}}


<!--After the soil samples are dried and bulk density is determined, the soil samples are often processed for loss-on-ignition (LOI), which is an estimate of how much ‘organic matter’ is a soil sample. Before the samples are put into the furnace, the soil sample needs to be crushed into a homogenous sample, often using a mortar and pestle. Depending on how much organic matter is in the sample, this can be time consuming.-->

After the soil samples are dried and bulk density is determined, the soil samples are often processed for loss-on-ignition (LOI), which is an estimate of how much ‘organic matter’ is in a soil sample. Before the samples are put into the furnace, the sediment needs to be crushed into a homogenous sample, often using a mortar and pestle. 

{{< gallery 
caption="Using a mortar and pestle to grind a sediment sample. Images by Brittney Roughan." >}}
    {{< gallery-img src="images/mortar1.jpg" >}}
    {{< gallery-img src="images/mortar2.jpg" >}}
{{< /gallery >}}


<!--LOI involves combusting the soil sample at a high temperature (550 ℃) in a muffle furnace for 4 hours. Before the soil samples are put into the furnace, they are placed in a ceramic crucible and weighed to a consistent starting weight. After the samples are combusted, they are re-weighed to determine how much mass was lost, which corresponds to how much organic matter was burnt off from the sample and is represented by ‘% organic matter’ of the sample. Sometimes accidents happen but often duplicate or triplicate samples are done for LOI, so it can take a significant amount of time to get through that many samples. Soil carbon scientists often use different methods for LOI, which may affect the comparison of results between datasets. As there is no standard method, it is recommended to report and be consistent in three parameters: ignition temperature, exposure time, and starting weight.-->

LOI involves combusting the soil sample at a high temperature (550 ℃) in a muffle furnace for 4 hours. First, each sample is put in a ceramic crucible and weighed to a consistent starting weight. After the samples are combusted, they are re-weighed to determine how much mass was lost, which corresponds to how much organic matter was burnt off from the sample and is represented by ‘% organic matter’ of the sample. Sometimes accidents happen but often duplicate or triplicate samples are done for LOI, so it can take a significant amount of time to get through a set of samples. Soil carbon scientists often use different methods for LOI, which may affect the comparison of results between datasets. As there is no standard method, Heiri et al. (2001) <a href="../references/">[2]</a> recommend reporting and being consistent in three parameters: ignition temperature, exposure time, and starting weight. 

<!--{{< gallery 
caption="Images by Brittney Roughan." >}}
    {{< gallery-img src="images/loi1.jpg" >}}
    {{< gallery-img src="images/loi2.jpg" >}}
    {{< gallery-img src="images/loi3.jpg" >}}
{{< /gallery >}}-->

{{< gallery 
caption="Samples in the muffle furnace after combustion. Images by Brittney Roughan." >}}
    {{< gallery-img src="images/loi1.jpg" >}}
    {{< gallery-img src="images/loi2.jpg" >}}
{{< /gallery >}}

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






