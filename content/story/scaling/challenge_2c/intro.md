---
weight: 1 # the order to render
name: "intro" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "How to consider non-linearities?"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 80 # translates to % of browser window
align: "center" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
splash: true # display the title and subtitle above the panel
layers: "google_satellite,mendes_study_area" # basemap and overlaying layers
zoom: 10
lat: 46.842
lng: -71.565
---
###  Introduction

Often we assume a relationship between two variables is linear; however, if we increase the spatial extent we may see a nonlinear relationship appear. This is important, because we often predict in areas outside of where we sample. If we assume a relationship is linear, when it is not, then our extrapolations will be incorrect.