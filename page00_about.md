---
layout: page
title: About
description:
img: corona_virus_goodsell.jpg
caption: "Courtesy of David S. Goodsell"
permalink: /
sidebar: true
---

<hr>

# {{ site.data.about.title }}
{{ site.data.about.authors }}

{% for entry in site.data.about %}
{% if entry[0] != 'title' and entry[0] != 'authors' and entry[0] != 'Daily Rhythm' %}
## {{ entry[0] }}
{{ entry[1] }}
{% endif %}
{% endfor %}

