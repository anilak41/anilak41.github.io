---
layout: archive
title: "Proceedings"
permalink: /proceedings/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<ol>
{% for post in site.proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}
</ol>

