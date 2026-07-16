---
title: "电动力学"
permalink: /electrodynamics/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/diandong-lixue/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
