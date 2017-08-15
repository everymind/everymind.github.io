---
layout: archive
permalink: /open-notebook/
title: "EveryMind's Open Notebook Blog"
author_profile: false
---

This blog serves as a shared, online open lab notebook for EveryMind Online projects.  

{% include group-by-array collection=site.posts field="categories" %}

{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
