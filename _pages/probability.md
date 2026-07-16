---
title: "概率论"
permalink: /probability/
layout: single
toc: true
---

{% for file in site.static_files %}
{% if file.path contains "/pdfs/gailv-lun/" and file.extname == ".pdf" %}
- [{{ file.basename | replace: "_", " " }}]({{ file.path }})
{% endif %}
{% endfor %}
