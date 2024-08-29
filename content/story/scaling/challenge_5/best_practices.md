---
weight: 4 # the order to render
name: "best_practices" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Best practices and opportunities"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 80 # translates to % of browser window
align: "center" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
# splash: true # display the title and subtitle above the panel
layers: "google_satellite" # basemap and overlaying layers
zoom: 6
lat: 53.3701121
lng: -132.010678
---
### Best practices and opportunities
Models are very sensitive to the input data, so the more accurate the input data, the higher the reliability of the model. On the other hand, models are developed to be applied at a certain scale (spatial and temporal), and most times they are not useful to be directly applied at other scales. A model acceptable at one scale might not be at another. Another important consideration: Model evaluation can be a complex process itself. The larger the spatial and temporal scale of the phenomena, the evaluation of the model is more complex and challenging. 

Taking this into account, we suggest the following to improve reliability of model:
- Be clear about the purpose of the model. And verify that it applies to the scale considered. 
- Document all decisions made regarding the input data (sources, decisions made to incorporate it, etc.).
- Create clear and explicit criteria for every step of the model evaluation. Always document what you did and why!
- Conduct a sensitivity analysis to test the consistency of the model under a range of input parameters.