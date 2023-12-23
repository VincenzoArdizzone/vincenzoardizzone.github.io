layout: default
title: "Blog"
---

I am a physicist at the Italian Institute of Nanotechnology and an European Patent Attorney



{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
