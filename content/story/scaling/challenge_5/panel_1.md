---
weight: 1
name: "challenge_5"
layers: "esri_topo"
zoom: 2
lat: 45.1856
lng: -73.6853
# background_media : "img/title-bg.jpg" 
# background_media : "" 
background_img: "img/title-bg.jpg" 
visible: true
layout: "wide_over_bg"
#layout: "float_card"
menu_group: "Navigation"
menu_name: "Spatial resolution"
splash: true
title: "Model comparisons"

---

<!--Leaflet map in background with 3 different model output layers.-->

# Model comparisons

When selecting the level of detail to conduct research, scientists must balance between the generalizability, complexity, accuracy, and spatial extent of the analysis. As an example, the evaluation of the Human Footprint on ecosystems varies at multiple scales.

# Introduction

Decision-making and research questions are meaningful at specific scales and often need scale-specific models.
Choosing the right size to study natural phenomena is hard for scientists (Oreskes et al., 1994). The scale chosen will determine how much detail and how accurate the model is. Also, how much area the model can cover. The scale of a study significantly impacts the models complexity, their accuracy, spatial extent, and generalizability (Brimicombe, 2010).
Researching at a local scale or a small proportion of the territory requires more complex analyses. Researchers need to consider more variables and their relationships to achieve a reliable approximation of the natural phenomena under investigation. Also, the identification of patterns could be more difficult at smaller scales. Furthermore, obtaining more detailed results demands more computational resources. Nevertheless, higher scales at a finer resolution do not always lead to higher accuracy (Brimicombe, 2010).
On the other hand, examining natural phenomena at larger scales, such as regional or global studies, may enhance comprehension of the phenomena. Coarser resolutions lead to reduced complexity, simplifying models’ inputs and outputs. Also, some relationships or patterns emerge to significant geographical extents. Furthermore, policymakers tend to favor regional and global scales, as they provide a broader perspective on reality (Brimicombe, 2010; Woolmer et al., 2008).

{{< figure src="images/unknownSourceAskM.png" title="Model comparisons" class="w-100 p-3">}}

## Case study: Human pressures at different scales

Here, we compared the Human footprint at three scales: global (Williams et al., 2020), national (Hirsh-Pearson et al., 2022), and provincial. The human footprint is a cumulative index that quantifies the extent and the intensity of human pressures on ecosystems and biodiversity.
This example represents the state of human pressures in the northeast of British Columbia. From coarse (global) to detailed (provincial) scales, we can easily identify how roads are represented to different extents. The global model captures a broad perspective of human interventions, in which roads and settlements are the most visible features. This global map is improved with the national model, which integrates 12 layers, providing the appearance of more levels of detail such as oil and gas infrastructure and mining. The provincial map, which incorporates 16 layers, shows a more comprehensive state of the human footprint, including seismic lines, oil and gas wells, and infrastructure, and even recreational features.

<!-- Leaflet map with ability to turn on and off the following three layers: Data/Originals_tiles/-->
<!-- Miguel's raster cell size comparison, large data file -->

# Best practices and opportunities

Models are very sensitive to the input data, so the more accurate the input data, the higher the reliability of the model. On the other hand, models are developed to be applied at a certain scale (spatial and temporal), and most times they are not useful to be directly applied at other scales. A model acceptable at one scale might not be at another. Another important consideration: Model evaluation can be a complex process itself. The larger the spatial and temporal scale of the phenomena, the evaluation of the model is more complex and challenging. 
Taking this into account, we suggest the following to improve reliability of model:
* Be clear about the purpose of the model. And verify that it applies to the scale considered. 
* Document all decisions made regarding the input data (sources, decisions made to incorporate it, etc.).
* Create clear and explicit criteria for every step of the model evaluation. Always document what you did and why!
* Conduct a sensitivity analysis to test the consistency of the model under a range of input parameters.

# References

Brimicombe, A. (2010). GIS, Environmental Modeling and Engineering. CRC Press.

Hirsh-Pearson, K., Johnson, C. J., Schuster, R., Wheate, R. D., Venter, O., & Hirsh, K. (2022). Canada’s human footprint reveals large intact areas juxtaposed against areas under immense anthropogenic pressure. Https://Doi.Org/10.1139/Facets-2021-0063, 7, 398–419. https://doi.org/10.1139/FACETS-2021-0063

Oreskes, N., Shrader-Frechette, K., & Belitz, K. (1994). Verification, validation, and confirmation of numerical models in the earth sciences. Science, 263(5147), 641–646. https://doi.org/10.1126/science.263.5147.641

Williams, B. A., Venter, O., Allan, J. R., Atkinson, S. C., Rehbein, J. A., Ward, M., Di Marco, M., Grantham, H. S., Ervin, J., Goetz, S. J., Hansen, A. J., Jantz, P., Pillay, R., Rodríguez-Buriticá, S., Supples, C., 
Virnig, A. L. S., & Watson, J. E. M. (2020). Change in Terrestrial Human Footprint Drives Continued Loss of Intact Ecosystems. One Earth, 3(3), 371–382. https://doi.org/10.1016/j.oneear.2020.08.009

Woolmer, G., Trombulak, S. C., Ray, J. C., Doran, P. J., Anderson, M. G., Baldwin, R. F., Morgan, A., &    Sanderson, E. W. (2008). Rescaling the Human Footprint: A tool for conservation planning at an ecoregional scale. Landscape and Urban Planning, 87(1), 42–53. https://doi.org/10.1016/j.landurbplan.2008.04.005


