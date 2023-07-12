---
layout: archive
title: "Posters"
permalink: /posters/
author_profile: true
---

We will list posters here

{% include base_path %}

{% for post in site.posters reversed %}
  {% include archive-single.html %}
{% endfor %}
