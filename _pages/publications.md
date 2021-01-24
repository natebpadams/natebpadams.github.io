---
layout: archive
title: "Research"
permalink: /publications/
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /headers/l8a4070-2000x1333.jpg
author_profile: true
author_profile: true
---

I am an enzymologist and biophysist, exploring how nature’s nanomachines drive the chemical reactions that sustain life. I’ve used these skills to understand how plants turn green, how to stabalize artifical proteins and how marine organisms harvest scarce elements in the ocean. 

## Chlorophyll Biosynthesis

<img src='/images/chlorophyllres.png'><br>

I spent 12 years studying the enzymes that construct arguably the most important molecule on Earth, chlorophyll.  Billions of tonnes of this molecule are produced annually, but only until recently did we uncover every single step in the process. I discovered key mechanistic insights into how the enzymes perform their transformations, combining biophysics, enzymology and structural biology to understand the chlorophyll metabolon.

## Phosphorus uptake in bacteria

<img src='/images/ptres.png'><br>

Phosphorus is a vital element for all life, it makes up the back bone to DNA, life uses the bond between oxygen and phosphorus to power many chemical reactions, and it provides the buffering environment in our cells – but it can be difficult to find in the ocean. Marine bacteria have developed specialised machinery to scavage as much phosphorus as possible – and I’ve been exploring how this works.

## Publication list
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
