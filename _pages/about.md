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

I am currently a postdoctoral fellow in the **MosAIk** team of **LORIA (CNRS)** in Nancy. My work focuses on **topic modeling**, **distributional semantics** and **complex networks**. Within these fields, I'm interested in building **interpretable** representations of words, collections of documents and graphs with a reduced footprint (**frugal**). I am part of the SUMINO project which aims at designing lightweight **mono and multidocument summarization** methods for domain-specific data using knowledge graphs.

Previously, I was a teaching fellow and graduated with a PhD from _Le Mans Université_. I was part of the Language and Speech Technology Team of LIUM. During my thesis, entitled **_"Graphs, Words, and Communities: converging paths to interpretability with a frugal embedding framework"_**, I developed a framework to extract word and graph embeddings relying on methods from NLP and complex networks. 

I taught computer science as a teacher assistant in the science departement and at the ENSIM engineering school (algorithmics and programming in python, logic programming, database design and administration, NLP, or complex netwoks theory and complexity).

Before my PhD, I graduated with a MSc in natural language processing (ATAL) from the University of Le Mans. I also spent a year abroad at HAW Hamburg (Hamburg University of Applied Sciences) during my BSc in computer science at _Université de Tours (Blois)_.

Publications
=====

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
