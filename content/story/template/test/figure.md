---
weight: 1
name: "figure"
layers: "google_satellite"
zoom: 5
lat: 55.0
lng: -97.0
background_media : "images/title-bg.jpg" 
# background_media : "../img/montreal.jpeg" 
visible: true
layout: "panel_float_card"
splash: true
title: "Figures and Galleries"
# subtitle: "Figure"
opacity: 1
# align: "right"
# width: 50
---
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed iaculis lectus consequat ex viverra, id sagittis tortor interdum. Vestibulum sollicitudin pellentesque mi, quis malesuada mauris pulvinar eu. Nunc ut lacus ac erat eleifend ornare. Morbi eget cursus nulla. Aliquam at porttitor mi, vel viverra velit. Maecenas ex neque, varius et neque id, viverra ullamcorper erat. Quisque commodo nisl ut ex varius venenatis. Etiam vel tortor sapien. Aliquam id scelerisque lacus, at ultricies nibh. Vivamus posuere feugiat lacus, ac lacinia ante sagittis eu.


{{< figure src="images/landscape.jpg" caption="landscape" >}}  
{{< figure src="images/landscape.jpg" caption="landscape" class="w-100">}}  
{{< figure src="images/landscape.jpg" caption="landscape" class="w-50">}}  
{{< figure src="images/landscape.jpg" caption="landscape" class="w-50 float-end">}}  
{{< figure src="images/landscape.jpg" caption="landscape" class="w-50 float-start">}}  
{{< figure src="images/landscape.jpg" caption="landscape" class="w-25 float-end">}}  

{{< figure src="images/landscape.jpg" caption="landscape" class="w-25 d-block mx-auto">}}  


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed iaculis lectus consequat ex viverra, id sagittis tortor interdum. Vestibulum sollicitudin pellentesque mi, quis malesuada mauris pulvinar eu. Nunc ut lacus ac erat eleifend ornare. Morbi eget cursus nulla. Aliquam at porttitor mi, vel viverra velit. Maecenas ex neque, varius et neque id, viverra ullamcorper erat. Quisque commodo nisl ut ex varius venenatis. Etiam vel tortor sapien. Aliquam id scelerisque lacus, at ultricies nibh. Vivamus posuere feugiat lacus, ac lacinia ante sagittis eu.


{{< gallery >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/portrait.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/portrait.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
{{< /gallery >}}

{{< gallery class="w-50" caption="Gallery Caption">}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/portrait.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/portrait.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
{{< /gallery >}}

{{< gallery class="content-gallery w-50 float-end" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/portrait.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/portrait.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
{{< /gallery >}}



{{< gallery class="content-gallery w-50 mx-auto" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/portrait.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
    {{< gallery-img src="images/portrait.jpg" >}}
    {{< gallery-img src="images/landscape.jpg" >}}
{{< /gallery >}}
