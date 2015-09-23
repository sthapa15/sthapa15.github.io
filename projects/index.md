---
layout: archive
title: "My Projects"
date: 2015-04-09T11:40:45-04:00
modified:
excerpt: "Overview of my projects"
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.projects %}
  {% include post-grid-port.html %}
{% endfor %}
</div><!-- /.tiles -->
