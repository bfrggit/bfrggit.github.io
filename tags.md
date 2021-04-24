---
layout: single
title: Tags
permalink: /blog/archives/tags/
---

{% for tag in site.tags %} {% assign tag_name = tag | first %} [<i class="fas fa-fw fa-tags" aria-hidden="true" /> {{ tag_name }}]({{ site.tag_archive.path }}{{ tag_name }}){: .btn .btn--light-outline} {% endfor %}
