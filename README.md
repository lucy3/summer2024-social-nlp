---
layout: home
title: Social NLP
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Social NLP
---
# Social Aspects of Natural Language Processing

This interdisciplinary course offers a sampler of socially meaningful research questions that intersect with the field of natural language processing (NLP). We'll discuss issues around fairness in NLP, such as methodological pitfalls of working with sociocultural data and how biases may arise throughout the language model (LM) development pipeline. In addition, we'll cover how computational social science and cultural analytics can both drive methodological innovation for NLP and uncover substantive findings for the social sciences and humanities. Finally, we'll learn about the emerging intersection of HCI & NLP, which is becoming ever more needed as LMs are deployed in real-world applications in an interactive manner. 

{% for module in site.modules %}
{{ module }}
{% endfor %}
