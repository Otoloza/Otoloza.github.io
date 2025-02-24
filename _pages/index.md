---
layout: home
author_profile: true
permalink: /
title: Welcome!



feature_row:
  - image_path: /images/WD.png
    title : "white dwarfs"
    alt: "white dwarfs"
    excerpt: 'physics, evolution, and their connection to planetary systems'
    image_caption: "[from Warwick](https://warwick.ac.uk/newsandevents/pressreleases/thousands_of_stars/)"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row2:
  - image_path: /images/cv.png
    title : "Accreting white dwarfs" 
    alt: "Accreting white dwarfs"
    excerpt: 'white dwarfs accreting via Roche lobe overflow from non-degenerate companions (e.g. cataclysmic variables)'
    image_caption: "[University of Athens Observatory](http://observatory.phys.uoa.gr/research_cataclysmic_en.html)"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

## About me...

I am postdoctoral fellow at the recently formed astronomy and astrophysics group at the [USM](https://fisica.usm.cl/investigacion/astrofisica/) in Chile, which I must add, the campus is very. I am currently,  funded by a FONDECYT fellowship. I am mainly observer (optical and ultraviolet spectroscopy and optical photometry)  thought I have attempted to do some theory (focused on binary evolution).

My main areas of research is whatever that contains a white dwarf. You can find a bit of more information in the <a href="{{ site.url }}{{ site.baseurl }}/research">Research section</a>.


<!-- Delete next line if you prefer not to have a feature row. -->
<br />
<br />



{% if page.feature_row %}
  {% include feature_row  type="left" %}
  {% include feature_row id="feature_row2" type="right" %}
{% endif %}

<!-- Delete previous lines if you prefer not to have a feature row. -->
