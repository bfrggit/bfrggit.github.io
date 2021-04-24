---
layout: single
title: Tags
permalink: /blog/archives/tags/
---

{% for tag in site.tags %} {% assign tag_name = tag | first %}
- [{{ tag_name }}]({{ site.tag_archive.path }}{{ tag_name }}) {% endfor %}
