---
layout: single
title: Categories
permalink: /blog/archives/categories/
---

{% for category in site.categories %} {% assign category_name = category | first %} [<i class="fas fa-fw fa-folder-open" aria-hidden="true" /> {{ category_name }}]({{ site.category_archive.path }}{{ category_name }}){: .btn .btn--light-outline} {% endfor %}
