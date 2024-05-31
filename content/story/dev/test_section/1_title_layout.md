---
weight: -1
name: "section_1"
layers: "google_satellite"
zoom: 5
lat: 55.0
lng: -97.0
background_media : "images/title-bg.jpg" 
# background_media : "../img/montreal.jpeg" 
visible: true
layout: "panel_card"
splash: true
title: "Panel Title"
subtitle: "Panel Subtitle"
---
# Header Level 1
## Header Level 2
### Header Level 3
#### Header Level 4
##### Header Level 5
###### Header Level 6

Paragraph 

**Bold Text**

*Italicized Text*

***Bold and Italic***


1. Ordered List
   1. Ordered List
2. Ordered List 

- Unordered List
  - Unordered List
- Unordered List

> Block Quote
> Block Quote Second Line

Super<sup>script</sup> 

Sub<sub>script</sub> 


`Inline Code`

<code>Code Block</code>
```html
<div class="testclass"><img src="images/temp-figure.jpg" class="w-50 p-3 float-start"></div>
<img src="images/temp-figure.jpg" class="w-50 p-3 float-start">
```

Term 1
: Definition 1

Term 2
: Definition 2

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


Here's a sentence with a footnote. [^1]

[^1]: This is the footnote. 


---

## Images
Using hugo shortcode: 
{{< figure src="images/temp-figure.jpg" title="Image Caption" class="w-50 p-3 float-start" >}}
{{< figure src="images/temp-figure.jpg" title="Image Caption" class="w-50 p-3 float-start" >}}

Using raw HTML in markdown: 
<div class="testclass"><img src="images/temp-figure.jpg" class="w-50 p-3 float-start"></div>
<img src="images/temp-figure.jpg" class="w-50 p-3 float-start">


Using markdown:  
![Test Figure](images/temp-figure.jpeg)

## Contents
- Text Formatting
- Panel Layouts
- Images
- Spatial 
