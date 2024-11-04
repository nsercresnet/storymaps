---
weight: 1 # the order to render
name: "intro" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Modelling at different scales"
subtitle: "Authors: Miguel Arias, Gabriela Torchio, Hugo Thierry"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 80 # translates to % of browser window
align: "center" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
splash: true # display the title and subtitle above the panel
layers: "google_satellite" # basemap and overlaying layers
zoom: 7
lat: 57.1701121
lng: -125.210678
---
### Introduction

{{< figure src="images/unknownSourceAskM_v2.png" 
class="float-end w-50 d-block" 
caption="Modelling at different spatial scales often involves trade-offs between model complexity, accuracy (and/or precision), generalization and spatial extent (or spatial resolution)." 
>}}

Decision-making and research questions are meaningful at specific scales and often need scale-specific models. 


<!-- Choosing the right size (extent) to study natural phenomena is hard for scientists (Oreskes et al., 1994 <a href="../references/">[18]</a>). The scale chosen will determine how much detail and how accurate the model is, and also, how much area the model can cover. The scale of a study significantly impacts the models complexity, their accuracy, spatial extent, and generalizability (figure on the right) (Brimicombe, 2010 <a href="../references/">[19]</a>).

Researching at a local scale or a small proportion of the territory requires more complex analyses. Researchers need to consider more variables and their relationships to achieve a reliable approximation of the natural phenomena under investigation. Also, the identification of patterns could be more difficult at smaller scales. Furthermore, obtaining more detailed results demands more computational resources. Nevertheless, higher scales at a finer resolution do not always lead to higher accuracy (Brimicombe, 2010 <a href="../references/">[19]</a>).

On the other hand, examining natural phenomena at larger scales, such as regional or global studies, may enhance comprehension of the phenomena. Coarser resolutions lead to reduced complexity, simplifying models’ inputs and outputs. Also, some relationships or patterns emerge to significant geographical extents. Furthermore, policymakers tend to favor regional and global scales, as they provide a broader perspective on reality.
-->

Selecting the appropriate extent and resolution to study natural phenomena poses a significant challenge for scientists (Oreskes et al., 1994 <a href="../references/">[18]</a>). The chosen extent dictates the area the model can encompass, while the selected spatial resolution determines the level of detail and accuracy the model achieves. Hence, the spatial extent and resolution of a study significantly affects model complexity, accuracy (and/or precision), and generalizability (figure on the right) (Brimicombe, 2010 <a href="../references/">[19]</a>).

Spatial models must address trade-offs between spatial resolution, complexity, accuracy (and/or precision), and generalizability, especially when applied across varying spatial extents. For models covering large extents (e.g., planetary/global models), simplicity is often favored to maintain generalizability and reduce computational demands. However, this can come at the cost of local accuracy; as such, large extent models may overlook fine-scale processes and heterogeneities. Conversely, models developed for smaller extents (e.g., provincial or municipal models) can afford to be more complex, incorporating detailed biophysical and socio-ecological variables to achieve higher accuracy and capture site-specific dynamics. Yet, these finely tuned models risk reduced generalizability when applied beyond their original context due to overfitting and the presence of unique local factors that do not scale up effectively. 


