---
layout: page
title: LRDs
description: Little Red Dots — and what is hiding inside them
img: assets/img/lrds_science.jpg
importance: 2
category: work
related_publications: false
---

**Little Red Dots** (LRDs) are the second extragalactic puzzle handed to us by JWST, after the UV-bright galaxies at high-z. Owed to their unique spectral shape and unresolved nature in the rest-frame optical, they are pretty easy to pick out in NIRCam images. This is, however, where the simplicity stops.

Over the last few years my work has followed this population from one interpretation to the next — from extreme black hole masses and surprisingly high number densities, to the emergence of the dense gas cocoon scenario, and most recently to the chemistry of the gas itself. What LRDs truly are remains an open question, and I suspect the answer will surprise us, which makes it all the more fun.

Below are my papers on the subject, most recent first.

---

### [The Ashes of Supermassive Stars](https://arxiv.org/abs/2609.09271)

*Kokorev et al. (2026)*

Using deep NIRSpec spectroscopy from the SPURS program, we stack four LRDs and measure the elemental abundances of the gas around the central engine directly, from UV absorption lines. It comes out magnesium-depleted and aluminium-enhanced at a metallicity of only 1% solar — an anomaly otherwise seen only in globular cluster stars. Ionization, geometry and dust cannot mimic it, but hot hydrogen burning in a fully convective supermassive star of at least 10<sup>4</sup> M<sub>⊙</sub> reproduces it, which is about 100 times more massive than any star in the present-day Universe. It ties LRDs to globular cluster formation and to the heavy seeds of the first black holes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="img-border-wrapper" style="border: 1px solid #8B2020; border-radius: 4px; overflow: hidden;">
            {% include figure.liquid loading="eager" path="assets/img/lrd_sms.png" title="Al enhancement and Mg depletion in LRDs" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>
<div class="caption">
    LRDs (red) sit far above star-forming galaxies (green) in [Al/Fe], and well below them in [Mg/Fe] — the same direction as Galactic globular cluster stars. The coloured tracks show hot hydrogen burning at 75–90 MK.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="img-border-wrapper" style="border: 1px solid #8B2020; border-radius: 4px; overflow: hidden;">
            {% include figure.liquid loading="eager" path="assets/img/lrd_sms_nucleo.png" title="Alpha capture versus hot hydrogen burning" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>
<div class="caption">
    Why the pattern is diagnostic. Alpha capture in ordinary massive stars (left) builds the even-Z elements Mg and Si and makes little of the odd-Z Al. Hot hydrogen burning in a fully convective star (right) does the opposite — it destroys Mg and enhances Al, which is exactly what the LRD stack shows.
</div>

---

### [The Deepest GLIMPSE of a Dense Gas Cocoon](https://ui.adsabs.harvard.edu/abs/2025arXiv251107515K/abstract)

*Kokorev et al. (2025)*

Nearly 30 hours of NIRSpec time on a single lensed LRD behind Abell S1063. The depth buys us the full Paschen series, the He I triplet, Fe II multiplets pumped by Lyα, and broad lines whose profiles are exponential rather than Gaussian — the signature of electron scattering in dense gas rather than of Keplerian rotation. Together these pin down a stratified cocoon of dense gas around the central engine, and let us measure its density, column and covering fraction rather than assume them.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <div class="img-border-wrapper" style="border: 1px solid #8B2020; border-radius: 4px; overflow: hidden;">
            {% include figure.liquid loading="eager" path="assets/img/lrd_cocoon.png" title="Physical picture of the dense cocoon" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>
<div class="caption">
    The physical picture the data point to: a stratified cocoon around the central engine, with the broad-line region inside, the He I triplet and Lyα-pumped Fe II further out.
</div>

---

### [Silencing the Giant](https://ui.adsabs.harvard.edu/abs/2024ApJ...975..178K/abstract)

*Kokorev et al. (2024), ApJ*

A z = 4.13 LRD in GOODS-N caught with the full set of NIRSpec medium-resolution gratings, which is rare enough to be worth the effort. Broad Hα (FWHM ~ 2500 km/s) and a broad Mg II doublet mark an accreting black hole — the first clear rest-UV AGN signature in an LRD — while the rest-optical continuum belongs to a massive (log M<sub>⋆</sub>/M<sub>⊙</sub> ~ 10.6) galaxy that quenched about 200 Myr earlier. Unusually for this population the black hole is *not* overmassive: M<sub>BH</sub>/M<sub>⋆</sub> ~ 0.04%, right on the local relation.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="img-border-wrapper" style="border: 1px solid #8B2020; border-radius: 4px; overflow: hidden;">
            {% include figure.liquid loading="eager" path="assets/img/lrd_giant.png" title="Multi-grating line fits to GN-72127" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>
<div class="caption">
    The full G140M + G235M + G395M spectrum of GN-72127, with fits to Mg II, Hβ+[O III] and Hα+[N II]+[S II]. Broad components are in green, narrow in blue.
</div>

---

### [A Census of Photometrically Selected LRDs at 4 &lt; z &lt; 9](https://ui.adsabs.harvard.edu/abs/2024ApJ...968...38K/abstract)

*Kokorev et al. (2024), ApJ*

A uniform colour- and size-based search across ~640 arcmin<sup>2</sup> of blank JWST/NIRCam fields, which turned up 260 candidates at 4 &lt; z &lt; 9 and, more importantly, a number density. If the rest-optical light is AGN-dominated, these reddened AGN are roughly 100 times more abundant than UV-selected quasars of the same magnitude. One or two exotic objects can be waved away; hundreds of them cannot.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="img-border-wrapper" style="border: 1px solid #8B2020; border-radius: 4px; overflow: hidden;">
            {% include figure.liquid loading="eager" path="assets/img/lrd_census.png" title="Bolometric luminosity function of LRDs" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>
<div class="caption">
    Bolometric luminosity functions in two redshift bins. LRDs (red) sit well above the extrapolated quasar luminosity function of Shen et al. (2020) (dashed).
</div>

---

### [UNCOVER: A Broad-line AGN at z = 8.50](https://ui.adsabs.harvard.edu/abs/2023ApJ...957L...7K/abstract)

*Kokorev et al. (2023), ApJL*

The spectroscopic identification of a broad-line AGN only ~570 Myr after the Big Bang, lensed by Abell 2744. Hβ has FWHM = 3439 ± 413 km/s, implying log M<sub>BH</sub>/M<sub>⊙</sub> = 8.17 ± 0.42 and accretion at ~40% of Eddington. With the host constrained to log M<sub>⋆</sub>/M<sub>⊙</sub> &lt; 8.7, that is a black-hole-to-host mass ratio of at least ~30% — orders of magnitude above local quasars. This "overmassive" problem is a large part of why the dense gas picture had to be invented.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <div class="img-border-wrapper" style="border: 1px solid #8B2020; border-radius: 4px; overflow: hidden;">
            {% include figure.liquid loading="eager" path="assets/img/lrd_uncover.png" title="Black hole to stellar mass relation" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>
<div class="caption">
    Black hole mass against host stellar mass. UNCOVER 20466 (red star) sits far above the local relations of Reines &amp; Volonteri (2015) and Greene et al. (2016).
</div>
