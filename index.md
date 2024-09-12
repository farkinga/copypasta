---
layout:     default
title:      Index
permalink:  /
---

<ul>
  {% for post in site.posts %}
    {% if post.title %}
      <a href="{{ post.url | relative_url }}" class="post-link">{{ post.title }}</a>
    {% endif %}
  {% endfor %}
</ul>
