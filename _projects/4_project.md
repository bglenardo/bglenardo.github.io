---
layout: page
title: Organic liquid TPC
description: (Gratta Group @ Stanford) Research and development of time projection chambers (TPCs) using room-temperature organic liquids as a detection medium.
img: assets/img/TMS_tpc_half_full.jpg
importance: 3
category: Past
---

During my postdoc in Giorgio Gratta's group at Stanford, we developed the first self-triggering time projection chambers using room-temperature liquids. Such detectors are dramatically simpler to operate than noble liquid TPCs, as they do not require cryogenics and related infrastructure. If scalable, they could be used for high-fidelity imaging of neutrino interactions (proposed in {}) or possibly for direction searches for dark matter. 





<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TMS_tpc_with_labels.jpg" title="with labels" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TMS_TPC_half_full.jpg" title="half full" class="img-fluid rounded z-depth-1" %}
    </div>

</div>
<div class="caption">
    Photos of the TMS TPC during filling (left) and with the PMT installed to read out Cherenkov light (right). 
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TMS_muon_track_event.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TMS_pair_production_event.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
