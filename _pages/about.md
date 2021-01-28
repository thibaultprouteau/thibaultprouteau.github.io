---
permalink: /
title: "Thibault Prouteau"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Biography
=====

After graduating with my BSc from the University of Tours and a year abroad at HAW Hamburg (Hamburg University of Applied Sciences), passionate with NLP since the beginning of my curriculum, I graduated with a MSc in natural language processing (ATAL) from the University of Le Mans. I am currently a PhD student at Laboratoire d’Informatique de l’Université du Mans (LIUM). My thesis aims at developing temporal and interpretable word representations (word embeddings) to detect and characterise neologisms in large text corpora, in the context of evolving language using transcribed INA corpora. Another goal is to evaluate gender bias and stereotypes over time. My work is at the crossroads o three domains: artificial intelligence, digital humanities and network theory.

Publications
=====

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
