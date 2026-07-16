---
title: "数论"
permalink: /number-theory/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/shulun/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
