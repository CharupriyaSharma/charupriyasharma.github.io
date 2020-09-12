---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on <u><a href="{{https://scholar.google.ca/citations?user=bniQQecAAAAJ&hl=enauthor.googlescholar}}">[my Google Scholar profile](https://scholar.google.ca/citations?user=bniQQecAAAAJ&hl=enauthor.googlescholar)</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
