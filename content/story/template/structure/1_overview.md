---
weight: 1
name: "markdown"
layers: "google_satellite"
zoom: 5
lat: 55.0
lng: -97.0
background_media : "images/title-bg.jpg" 
# background_media : "../img/montreal.jpeg" 
visible: true
layout: "panel_float_card"
splash: true
title: "Overview"
subtitle: "Components of a Storymap"
opacity: 1
# align: "right"
# width: 50
---
We use these terms to describe the components of a storymap:


- Storymap: A collection of one or more Sections.
- Section: A series of one or more Panels. Scrolling to the bottom of a section displays a link to the next section.
- Panel: Content displayed in the foreground. Scrolling to the bottom of a panel displays the next panel, and updates the leaflet layer as needed.
- Map: Leaflet map displayed in the background. The map extent and layers are controlled by the panels, and will update as the user scrolls to the next panel.

--- 

- package/license info