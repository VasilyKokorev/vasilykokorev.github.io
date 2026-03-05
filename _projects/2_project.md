---
layout: page
title: LRDs
description: Little Red Dots
img: assets/img/lrds_science.jpg
importance: 2
category: work
giscus_comments: true
---


Little Red Dots (LRDs) are the second (after UV bright galaxies at high-z) extragalactic puzzle handed to us after the launch of JWST. Owed to their unique spectral shape and unresolved nature in rest-frame optical, they are pretty easy to pick out in NIRCam images. This is, however, where the simplicity stops.

The true nature and the physics driving these objects remains elusive and enigmatic. At first, we thought these objects were very massive (and therefore old) galaxies at high-z <a href="https://ui.adsabs.harvard.edu/abs/2023Natur.616..266L/abstract">Labbé+2023</a>, however that didn't sit quite right. Making stars takes time, and the Universe is not infinitely old, so even at z~6 (less than 10% of its current age), that would require some unusual physics <a href="https://ui.adsabs.harvard.edu/abs/2023NatAs...7..731B/abstract">Boylan-Kolchin+2023</a>. Soon after, broad hydrogen lines were observed in the first spectra of LRDs <a href="https://ui.adsabs.harvard.edu/abs/2024ApJ...963..129M/abstract">Matthee+2024</a><a href="https://ui.adsabs.harvard.edu/abs/2023ApJ...954L...4K/abstract">Killi+2023</a>, and that flipped the whole interpretation on its head. LRDs are not massive evolved galaxies, they are red (and therefore dust obscured) Type I AGN. So far so good, however taking line widths and (dust corrected) luminosities at face value, meaning coming purely from rotation, has led to another issue. Black holes in LRDs were overmassive, and with very little to none UV emission, that means that the black-hole-to-host-mass ratios were extremely high, more than 10% compared to only 0.1% in the local Universe <a href="https://ui.adsabs.harvard.edu/abs/2023ApJ...957L...7K/abstract">Kocevski+2023</a><a href="https://ui.adsabs.harvard.edu/abs/2024A%26A...691A.145M/abstract">Maiolino+2024</a>. So, do all LRDs accrete at extreme rates, or maybe they all formed from heavy seeds? Sure, maybe if we saw only a few of them, but LRDs are extremely abundant <a href="https://ui.adsabs.harvard.edu/abs/2024ApJ...968...38K/abstract">Kokorev+2024</a><a href="https://ui.adsabs.harvard.edu/abs/2025ApJ...986..126K/abstract">Kokorev+2025a</a><a href="https://ui.adsabs.harvard.edu/abs/2025ApJ...991...37A/abstract">Akins+2025</a> at z>4, as it turns out. One or two objects with unusual formation pathways are fine, but not hundreds. Clearly some other piece was missing.

Together with revised bolometric corrections <a href="https://ui.adsabs.harvard.edu/abs/2026ApJ...996..129G/abstract">Greene+2026</a>, and little evidence of dust [?], the black hole masses are inching closer and closer to that coveted 0.1%. So as it stands, the consensus is, in the optical: LRDs are cocoons of stratified dense gas, supported by some highly energetic source (likely an active black hole) at its centre. In the UV: some UV radiation must come from the cocoon [?][?], but the host galaxies are definitely there, sometimes being very obvious disks <a href="https://ui.adsabs.harvard.edu/abs/2025arXiv251107515K/abstract">Kokorev+2025b</a><a href="https://ui.adsabs.harvard.edu/abs/2025arXiv251121820D/abstract">de Graaff+2025</a>.

Is it enough though? Only time will tell. Below are some of my papers on the subject.



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

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
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
