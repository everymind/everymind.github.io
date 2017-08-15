---
layout: archive
permalink: /open-notebook/
title: "EveryMind's Open Notebook Blog"
author_profile: false
---

This blog serves as a shared, online open lab notebook for EveryMind Online projects.  

{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
{% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
{% if year != written_year %}
<h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
{% capture written_year %}{{ year }}{% endcapture %}
{% endif %}
{% include archive-single.html %}
{% endfor %}
