---
title: "集合论"
permalink: /set-theory/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/jihe-lun/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
