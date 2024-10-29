---
layout: page
title: Factors affecting adherens junction complexes
description: Function of δ-catenin in cancer and factors affecting E-cadherin complex
img: assets/img/16.jpg
importance: 5
category: work
related_publications: he2016interaction, shrestha2017hakai, shrestha2018delta
published: true
---

<div style="text-align: justify">
<i>Chonnam National University, South Korea (2013-2017)</i><br><br>
<b>Overview</b>
<br><p>This project focuses on understanding the regulation and function of adherens junction proteins, particularly δ-catenin, in cancer progression. Adherens junctions are critical for maintaining cell-cell adhesion and epithelial integrity. Disruption of these junctions is a hallmark of the epithelial-mesenchymal transition (EMT), a key process driving cancer metastasis.</p>
<p>The δ-catenin protein is a member of the p120-catenin subfamily and has been found to be overexpressed in various cancers, including prostate, lung, ovarian, and colorectal cancers. Previous work has shown that δ-catenin can promote E-cadherin processing and activate oncogenic β-catenin signaling, suggesting an important role for δ-catenin in cancer progression. This project aims to further elucidate the mechanisms by which δ-catenin is regulated and how it contributes to cancer development and metastasis.</p>
<p>The project also investigates the role of other adherens junction proteins, such as E-cadherin and p120-catenin, in modulating δ-catenin function and cancer progression. Understanding the interplay between these proteins and their impact on cell-cell adhesion and signaling pathways will provide important insights into the complex regulation of the adherens junction and its implications in cancer. Overall, this project seeks to uncover novel mechanisms underlying the dysregulation of adherens junction proteins and their contribution to the hallmarks of cancer.</p>
</div>
<br>
<b> Key Findings<b><br>
<li>

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
