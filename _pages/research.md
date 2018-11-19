---
layout: archive
title: "Research"
permalink: /research/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

## Color gradients and z~1 galaxies

Quite different from their local buddies, z~1 galaxies are known to be considerably obscured by dust. In typical cases,more than 80% of the UV photons from star forming regions are blocked (see Wuyts et al. 2011, ApJ, 742, 96). Therefore in order to figure out where stars are born inside these galaxies, which is one of the most important questions of galaxy formation nowadays, dust extinction effect must be appropriately evaluated (the so-called age-dust degeneracy).

To hack this, I use spatial-resolved deep photometry as obtained by the [HST CANDELS](https://candels.ucolick.org/) to dissect the colors of z~1 star-forming galaxies (we really count on HST, because most of them are no larger than 1 arc second!). We adapt rest-frame UVJ color diagrams and map color gradients (the colors of galaxies as a function of radius) onto them. Special calibration is designed to infer star formation gradients and dust attenuation gradients based on HST broadband photometry.We also look forward to doing this beyond z~1, now hindered by the lack of high resolution mid-IR imaging necessary to derive rest-frame near-IR bands. But that's where [JWST](https://jwst.stsci.edu/) is coming to help hopefully soon. 

## Dust attenuation law and galaxy inclination

This is a work in progress. To be updated soon.
  

## The kinematic state of galaxies beyond local universe


This is another work in progress. To be updated.

[Here]('https://nbviewer.jupyter.org/github/WeichenStars/WeichenStars.github.io/blob/master/Galaxies_LSS_pencilgalaxy.ipynb?flush_cache=true') is a note about basic galaxy formation theories in a cosmological context I am curently developing. The note follows a minimalism fashion to help people, especially those working on galaxy observation but having little time to work through textbooks, reach to the concenpt of galaxy formation since the primodial CMB fluctuation fast and clearly.


Publications
===========
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
