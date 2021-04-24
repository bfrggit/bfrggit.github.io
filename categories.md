---
layout: single
title: Categories
permalink: /blog/archives/categories/
---

{% for category in site.categories %} {% assign category_name = category | first %}
- [{{ category_name }}]({{ site.category_archive.path }}{{ category_name }}) {% endfor %}
