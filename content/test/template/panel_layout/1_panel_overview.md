---
weight: 1
name: "panels"
title: "Panels"
subtitle: "All About Panels"
layers: "google_satellite"
zoom: 5
lat: 55.0
lng: -97.0
# background_media : "images/title-bg.jpg" 
visible: true
layout: "panel_float_card"
splash: false
opacity: 1
align: "center"
width: "50"
---

## Panels

Content is authored as a collection of panels within a section. Individual panels are written in markdown. They can include images, trigger map events on the map layer, and embed interactive widgets for displaying data.

The layout, appearance, and map actions for a panel are all defined in the frontmatter. This section will define the settings available and provide some examples. The actual content inside a panel is written below the frontmatter in markdown, and is discussed in the next section. 

### Frontmatter Settings

#### Title and Organization
```yaml
weight: 1 # the order to render
name: "panels" # must be unique within section and not include special characters
visible: true # whether to include this panel in the output, useful for testing
title: "Panels" # human friendly title. KEEP IT SHORT
subtitle: "All About Panels" # a longer description to be displayed under the title, in some places
```

#### Layout
```yaml
layout: "panel_float_card" # template to use
opacity: [0:1] # lower values show more of the underlying map
width: [0:100] # translates to % of browser window
align: [center|left|right] # align the entire panel
background_media : "images/title-bg.jpg"  # background image rendered behind the panel, covering map
splash: false # display the title and subtitle above the panel

```

#### Spatial Controls
These will be covered in depth in a following section. The important note here is that each panel should include these settings to prevent errors. We're working on a solution where undefined parameters will default to a story-wide setting or the previous panel's setting.

```yaml
layers: "google_satellite" # basemap and overlaying layers
zoom: 5 # zoom level
lat: 55.0 # focal lat
lng: -97.0 # focal long
```
