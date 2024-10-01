---
weight: 1 # the order to render
name: "intro" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Making good predictions"
subtitle: "Authors: Poliana Mendes, Amanda Schwantes"
layout: "panel_float_card" # template to use
opacity: 1 # lower values show more of the underlying map
width: 80 # translates to % of browser window
align: "center" # align the entire panel
# background_media : "images/BackgroundTitleSlide1.jpg"  # background image rendered behind the panel, covering map
splash: true # display the title and subtitle above the panel
layers: "google_satellite" # basemap and overlaying layers
zoom: 10
lat: 46.842
lng: -71.565
---
###  Introduction

We often assume that a relationship between two variables is linear; however, if we increase or reduce the spatial extent of a study, we may see a nonlinear relationship appear. This matters because we often use data from one area to make predictions for other areas. If we assume the relationship is linear when it’s not, our predictions will be wrong.

