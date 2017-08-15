---
layout: archive
permalink: /open-notebook/
title: "Open Notebook Blog"
author_profile: true
---

This blog serves as a shared, online open lab notebook for EveryMind Online projects. Posts are organized by project below. 

:)

<h1>Archive of posts with {{ page.type }} '{{ page.title }}'</h1>
<ul class="posts">
  {% for post in page.posts %}
    <li>
      <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
